<template>
    <section class="relative py-16 max-md:px-10 my-20">
        <div aria-hidden="true"
            class="absolute inset-0 h-max w-full m-auto grid grid-cols-2 -space-x-52 opacity-20">
            <div class="blur-[106px] h-56 bg-gradient-to-br from-primary from-blue-700"></div>
            <div class="blur-[106px] h-32 bg-gradient-to-r from-cyan-400 to-indigo-600"></div>
        </div>
        <div>
            <div class="relative">
                <div class="mt-6 m-auto space-y-6 md:w-8/12 lg:w-7/12">
                    <img src="@/assets/icons/crow-dynamic-color.png" alt="community" class="w-36 mx-auto">
                    <h2 class="text-center text-4xl font-bold text-white md:text-5xl">Get Started now
                    </h2>
                    <p class="text-center text-xl  text-gray-300">
                        Kreyativ Community forum and discord was created for community members to connect with valuable
                        people in a quality environment, share information, discuss different topics, quick access to
                        information and better communication among community members. Members of the Kreyativ community
                        actively contributing to the forum/discord will help us grow and develop the community even further.
                    </p>
                    <div class="flex flex-wrap justify-center gap-6">
                        <a href="https://community.kreyativ.co/" class="btn">
                            <span class="relative text-base font-semibold text-dark">Join Forum</span>
                        </a>
                        <a href="https://discord.io/kreyativ" target="_blank"
                            class="relative flex h-12 w-full items-center justify-center px-8 before:absolute before:inset-0 before:rounded-full before:border before:border-transparent before:bg-primary/10 before:bg-gradient-to-b before:transition before:duration-300 hover:before:scale-105 active:duration-75 active:before:scale-95 before:border-gray-700 before:bg-gray-800 sm:w-max">
                            <span class="relative text-base font-semibold text-primary text-white">Join Our Discord
                                Server</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.btn {
  @apply max-sm:w-full }
</style>