<template>
    <section>
        <div class="container px-20 my-36">
            <div class="mb-12 space-y-2 text-center">
                <h2 class="text-3xl font-bold md:text-4xl text-white">Some Articles</h2>
                <p class="lg:mx-auto lg:w-6/12 text-gray-300">
                    Be the first to know about innovations by following the Kreyativ Blog!
                </p>
            </div>
            <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">
                <div
                    class="group p-6 sm:p-8 rounded-3xl shadow-none border-gray-700  bg-gray-800 bg-opacity-50 shadow-gray-600/10">
                    <div class="relative overflow-hidden rounded-xl">
                        <img src="@/assets/blog/ruby-blog.png"
                            alt="art cover" loading="lazy" width="1000" height="667"
                            class="h-64 w-full object-cover object-top transition duration-500 group-hover:scale-105" />
                    </div>
                    <div class="mt-6 relative">
                        <h3 class="text-2xl font-semibold text-white">
                            Wonders of The Ruby Programming Language
                        </h3>
                        <p class="mt-6 mb-8 text-gray-300">
                            Ruby, often referred to as a programmer's best friend, is a versatile and expressive...
                        </p>
                        <a  href="https://blog.kreyativ.co/node/2">
                            <span class="text-blue-300">Read more</span>
                            <img src="@/assets/icons/arrow-right.svg" alt="read more">
                        </a>
                    </div>

                </div>
                <div
                    class="group p-6 sm:p-8 rounded-3xl shadow-none border-gray-700 bg-gray-800 bg-opacity-50 shadow-gray-600/10">
                    <div class="relative overflow-hidden rounded-xl">
                        <img src="@/assets/blog/team-work.avif"
                            alt="art cover" loading="lazy" width="1000" height="667"
                            class="h-64 w-full object-cover object-top transition duration-500 group-hover:scale-105" />
                    </div>
                    <div class="mt-6 relative">
                        <h3 class="text-2xl font-semibold text-white">
                            What is a team?
                        </h3>
                        <p class="mt-6 mb-8 text-gray-300">
                            The concept of a team has been ingrained in human society since ancient times....
                        </p>
                        <a  href="#">
                            <span class="text-blue-300">Read more</span>
                            <img src="@/assets/icons/arrow-right.svg" alt="read more">
                        </a>
                    </div>

                </div>
                <div
                    class="group p-6 sm:p-8 rounded-3xl border-gray-700 bg-gray-800 bg-opacity-50 shadow-2xl shadow-gray-600/10">
                    <div class="relative overflow-hidden rounded-xl">
                        <img src="@/assets/blog/open-source.avif"
                            alt="art cover" loading="lazy" width="1000" height="667"
                            class="h-64 w-full object-cover object-top transition duration-500 group-hover:scale-105" />
                    </div>
                    <div class="mt-6 relative">
                        <h3 class="text-2xl font-semibold text-white">
                            Value of Open Source Projects
                        </h3>
                        <p class="mt-6 mb-8 text-gray-300">
                            Open source projects have revolutionized the world of software development,...
                        </p>
                        <a href="#">
                            <span class="text-blue-300">Read more</span>
                            <img src="@/assets/icons/arrow-right.svg" alt="read more">
                        </a>
                    </div>

                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
a {
    @apply items-center flex gap-4
}
a img{
    @apply w-4 transition-all opacity-0
}

a:hover img{
    @apply opacity-100 ml-2
}
</style>