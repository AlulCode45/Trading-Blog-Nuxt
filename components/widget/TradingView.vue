<template>
  <div
      class="tradingview-widget-container"
      style="width: 100%; height: 100%"
  >
    <div
        class="tradingview-widget-container__widget"
        style="width: 100%; height: 100%"
        ref="tradingViewWidget"
    ></div>
  </div>
</template>

<script>
export default {
  name: "WidgetTradingView",
  props: {
    symbol: {
      type: String,
      default: "BINANCE:BTCUSD",
    },
    interval: {
      type: String,
      default: "D",
    },
    timezone: {
      type: String,
      default: "Etc/UTC",
    },
    theme: {
      type: String,
      default: "light",
    },
    style: {
      type: String,
      default: "1",
    },
    locale: {
      type: String,
      default: "en",
    },
    allowSymbolChange: {
      type: Boolean,
      default: true,
    },
    calendar: {
      type: Boolean,
      default: false,
    },
  },
  mounted() {
    this.loadTradingViewWidget();
  },
  methods: {
    loadTradingViewWidget() {
      if (!this.$refs.tradingViewWidget) return;

      const script = document.createElement("script");
      script.type = "text/javascript";
      script.src =
          "https://s3.tradingview.com/external-embedding/embed-widget-advanced-chart.js";
      script.async = true;
      script.innerHTML = JSON.stringify({
        autosize: true, // Mengaktifkan autosize
        symbol: this.symbol,
        interval: this.interval,
        timezone: this.timezone,
        theme: this.theme,
        style: this.style,
        locale: this.locale,
        allow_symbol_change: this.allowSymbolChange,
        calendar: this.calendar,
      });
      this.$refs.tradingViewWidget.appendChild(script);
    },
  },
};
</script>

<style scoped>
.tradingview-widget-container {
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100%;
}
.tradingview-widget-container__widget {
  flex: 1;
}
</style>
