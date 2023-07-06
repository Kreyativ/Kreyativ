<template>
    <div class="container mt-40 px-6 py-16 mx-auto">
        <div class="text-center">
            <p class="font-medium text-blue-500 dark:text-blue-400">Contact us</p>

            <h1 class="mt-2 text-2xl font-semibold text-gray-800 md:text-3xl dark:text-white">Get in touch</h1>

            <p class="mt-3 text-gray-500 dark:text-gray-400">Our friendly team is always here to chat.</p>
        </div>

        <div class="grid grid-cols-1 gap-12 mt-10 md:grid-cols-2 lg:grid-cols-3">
            <div class="contact-card">
                <span class="p-3 text-blue-500 rounded-full bg-blue-100/80 dark:bg-gray-800">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                    </svg>
                </span>

                <h2 class="mt-4 text-lg font-medium text-gray-800 dark:text-white">Email</h2>
                <p class="mt-2 text-gray-500 dark:text-gray-400">Our friendly team is here to help.</p>
                <a href="email:office@kreyativ.co" class="mt-2 text-blue-500 dark:text-blue-400">office@kreyativ.co</a>
            </div>

            <div class="contact-card">
                <span class="p-3 text-blue-500 rounded-full bg-blue-100/80 dark:bg-gray-800">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                    </svg>
                </span>
                
                <h2 class="mt-4 text-lg font-medium text-gray-800 dark:text-white">Office</h2>
                <p class="mt-2 text-gray-500 dark:text-gray-400">Come say hello at our office HQ.</p>
                <p class="mt-2 text-blue-500 dark:text-blue-400">America, Colorado</p>
            </div>

            <div class="contact-card">
                <span class="p-3 text-blue-500 rounded-full bg-blue-100/80 dark:bg-gray-800">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                    </svg>
                </span>
                
                <h2 class="mt-4 text-lg font-medium text-gray-800 dark:text-white">Phone</h2>
                <p class="mt-2 text-gray-500 dark:text-gray-400">Mon-Fri from 8am to 5pm.</p>
                <p class="mt-2 text-blue-500 dark:text-blue-400">+1 (000) 000-0000</p>
            </div>
        </div>
    </div>
    <section class="container mt-10 mx-auto lg:flex relative lg:justify-center">
        <div class="animate-pulse absolute blur-3xl bg-gradient-to-tr from-black to-blue-400 bg-opacity-20 w-full h-1/2 z-[-1] top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2"></div>
    <div
        class="overflow-hidden bg-gray-900 border border-[#393939] lg:mx-8 lg:flex lg:max-w-6xl lg:w-full lg:shadow-md lg:rounded-xl">
        <div class="lg:w-1/2">
            <img class="h-64 bg-cover md:w-full lg:h-full max-md:hidden" src='@/assets/star-slide.jpg'>
        </div>

        <div class="max-w-xl px-6 py-12 lg:max-w-5xl lg:w-1/2">
            <h2 class="text-2xl font-semibold md:text-3xl">
                Support  <span class="text-blue-500">us</span> on Patreon

            </h2>

            <p class="mt-4">
                Making a contribution through our Patreon will reward you with access to our development Discord and your name listed on this page.
            </p>

            <a href="https://patreon.com/kreyativ" target="_blank" class="transition-all cursor-pointer hover:scale-105 inline-flex w-full mt-6 sm:w-auto">
                <div class="relative group"><div class="absolute -inset-0.5 bg-gradient-to-r from-pink-600 to-purple-600 rounded-lg blur opacity-75 group-hover:opacity-100 transition duration-1000 group-hover:duration-200 animate-tilt"></div><div class="relative px-6 py-3 bg-gray-200 text-black rounded-lg">Let's Go!</div></div>
            </a>
        </div>
    </div>
</section>
</template>

<style>
.contact-card {
   @apply  bg-[#202020] border rounded-xl border-[#393939] py-20 flex flex-col items-center justify-center text-center
}

</style>