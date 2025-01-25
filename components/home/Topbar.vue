<template>
    <header>
        <div class="flex justify-between items-center max-w-7xl mx-auto p-4">
            <div class="logo flex items-center">
                <img src="/public/favicon.ico" alt="logo" />
                <h1 class="text-md font-semibold ml-2">ATrade</h1>
            </div>
            <nav>
                <ul class="flex items-center space-x-5">
                    <li><a href="#" :class="[
                        'hover:text-blue-500',
                        'hover:font-bold',
                        'transition-all',
                        'hover:border-b-2',
                        'hover:border-b-blue-500'
                    ]">Home</a></li>
                    <li><a href="#" :class="[
                        'hover:text-blue-500',
                        'hover:font-bold',
                        'transition-all',
                        'hover:border-b-2',
                        'hover:border-b-blue-500'
                    ]">Articles</a></li>
                    <li><a href="#" :class="[
                        'hover:text-blue-500',
                        'hover:font-bold',
                        'transition-all',
                        'hover:border-b-2',
                        'hover:border-b-blue-500'
                    ]">Analysis</a></li>
                    <li><a href="#" :class="[
                        'hover:text-blue-500',
                        'hover:font-bold',
                        'transition-all',
                        'hover:border-b-2',
                        'hover:border-b-blue-500'
                    ]">Join Member</a></li>
                    <HomeButton buttonText="Sign In" />
                </ul>
            </nav>
        </div>
    </header>
</template>