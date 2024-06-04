<script setup></script>

<template>
    <div class="container mx-auto px-5">
        <header class="flex justify-between py-12 items-center">

            <div>
                <a href="/"><img src="/images/logo-bookmark.svg" alt="Site Logo"></a>
            </div>
            
            <nav class="flex justify-end flex-col md:flex-row">
                <button @click="toggleMobileNav()" type="button" class="flex md:hidden focus:outline-none">
                    <svg viewBox="0 0 24 24" class="h-6 w-6 fill-current">
                        <path fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"></path>
                    </svg>
                </button>

                <ul class="space-x-10 font-theme-heading font-medium items-center hidden md:flex  flex-col space-y-7 md:space-y-0 md:flex-row">
                    <li class="uppercase hover:text-theme-secondary transition duration-200"><a href="#subscribe" v-smooth-scroll>Подписаться</a></li>
                    <a href="https://disk.yandex.ru/d/hsZWWqo_O84Ztg" class="uppercase hover:text-theme-secondary transition duration-200">Скачать Telegram</a>
                </ul>
            </nav>
        </header>    
    </div>
</template>