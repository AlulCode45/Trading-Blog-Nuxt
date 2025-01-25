<template>
    <div>
        <button :class="[
            backgroundColor || 'bg-green-500',
            textColor || 'text-white',
            'hover:bg-green-700 font-bold py-2 px-4 rounded-full '
        ]" @click="$emit('handleClick')">
            {{ buttonText }}
        </button>
    </div>
</template>

<script>
export default {
    props: {
        buttonText: {
            type: String,
            required: true,
        },
        backgroundColor: {
            type: String,
            default: '',
        },
        textColor: {
            type: String,
            default: '',
        },
    },
    emits: ['handleClick']
}
</script>

<style lang="scss" scoped></style>
