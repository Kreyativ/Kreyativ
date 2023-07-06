<template>
  <section>
    <div class="mx-auto container mt-20 text-gray-300 text-lg">
      <div
        class="space-y-6 justify-between text-gray-600 md:flex flex-row-reverse md:gap-6 md:space-y-0 lg:gap-12 lg:items-center">
        <div class="md:5/12 lg:w-1/2 relative flex justify-center items-center">
          <img src="@/assets/blur17.png" class=" animate-pulse absolute z-[-1] opacity-90 blur-3xl w-4/5 top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2" alt="">
          <img src="@/assets/target-dynamic-color.png" alt="image" loading="lazy" width="" height="" class="w-full" />
        </div>
        <div class="md:7/12 lg:w-1/2">
          <div class="flex items-center gap-4">
            <div class="bg-gray-100 inline-block rounded-full p-4">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                class="w-6 h-6 text-blue-500  ">
                <path fill-rule="evenodd"
                  d="M2.25 13.5a8.25 8.25 0 018.25-8.25.75.75 0 01.75.75v6.75H18a.75.75 0 01.75.75 8.25 8.25 0 01-16.5 0z"
                  clip-rule="evenodd" />
                <path fill-rule="evenodd"
                  d="M12.75 3a.75.75 0 01.75-.75 8.25 8.25 0 018.25 8.25.75.75 0 01-.75.75h-7.5a.75.75 0 01-.75-.75V3z"
                  clip-rule="evenodd" />
              </svg>
            </div>
            <h2 class="text-3xl font-bold md:text-4xl">
              Our Mission
            </h2>
          </div>
          <hr class="mt-10 mb-16 border-gray-600 w-2/6" />
          <p class="my-8 text-gray-300">
            Kreyativ will continue to make a difference in many sectors with its always innovative projects.
            With its unique vision and working principles, this company, which aims to be appreciated worldwide, is a
            promising company for the future.
            perspective on the world's technological and societal challenges. <br> <br> To help solve technological and
            societal challenges around the world and lead the way to a much better future.
            we are trying to evolve. <br> <br> We want to work on issues such as open source software, artificial
            intelligence, digital freedoms and education, and
            We aim to work in a way that is inclusive of all segments of society.

            To realize these goals, Kreyativ uses innovative technologies and approaches.
          </p>
          <div class="divide-y space-y-4 divide-gray-800">
            <div class="pt-4 flex gap-4 md:items-center relative border-gray-400 border p-4 bg-logo rounded-lg">
              <div class="absolute w-full h-full bg-[#303030] opacity-20 blur-3xl"></div>
              <img src="@/assets/brand/logo.svg" alt="Kretativ Logo" class="z-10 w-1/12">
              <div class="w-5/6 z-10">
                <h4 class="font-semibold text-lg text-gray-200 bg-opacity-80 px-6 py-2 bg-[#1e2637] border-[#1e2637] border w-fit rounded-full">Kreyativ LLC Logo</h4>
                <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img class="mt-4"
                    alt="Creative Commons License" style="border-width:0"
                    src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br /> <span class="underline text-gray-100">This work is licensed under a</span> 
                <a class="font-bold text-blue-400" rel="license"
                  href="http://creativecommons.org/licenses/by-nc-nd/4.0/"> Creative Commons
                  Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>


<style>
.bg-logo {
  background-image: radial-gradient(ellipse at bottom right, var(--tw-gradient-stops));
  --tw-gradient-from: #94a3b8 var(--tw-gradient-from-position);
    --tw-gradient-to: rgb(148 163 184 / 0) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
    --tw-gradient-to: rgb(168 85 247 / 0)  var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-from), #a955f7 var(--tw-gradient-via-position), var(--tw-gradient-to);
    --tw-gradient-to: #38bff8 var(--tw-gradient-to-position);
    backdrop-filter: 200px;
}
</style>