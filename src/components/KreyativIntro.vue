<template>
  <section>
    <div class="container text-lg">
      <div class="w-full">
        <div class="bg-blue-500 inline-block rounded-full p-4">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
            <path fill-rule="evenodd"
              d="M9 4.5a.75.75 0 01.721.544l.813 2.846a3.75 3.75 0 002.576 2.576l2.846.813a.75.75 0 010 1.442l-2.846.813a3.75 3.75 0 00-2.576 2.576l-.813 2.846a.75.75 0 01-1.442 0l-.813-2.846a3.75 3.75 0 00-2.576-2.576l-2.846-.813a.75.75 0 010-1.442l2.846-.813A3.75 3.75 0 007.466 7.89l.813-2.846A.75.75 0 019 4.5zM18 1.5a.75.75 0 01.728.568l.258 1.036c.236.94.97 1.674 1.91 1.91l1.036.258a.75.75 0 010 1.456l-1.036.258c-.94.236-1.674.97-1.91 1.91l-.258 1.036a.75.75 0 01-1.456 0l-.258-1.036a2.625 2.625 0 00-1.91-1.91l-1.036-.258a.75.75 0 010-1.456l1.036-.258a2.625 2.625 0 001.91-1.91l.258-1.036A.75.75 0 0118 1.5zM16.5 15a.75.75 0 01.712.513l.394 1.183c.15.447.5.799.948.948l1.183.395a.75.75 0 010 1.422l-1.183.395c-.447.15-.799.5-.948.948l-.395 1.183a.75.75 0 01-1.422 0l-.395-1.183a1.5 1.5 0 00-.948-.948l-1.183-.395a.75.75 0 010-1.422l1.183-.395c.447-.15.799-.5.948-.948l.395-1.183A.75.75 0 0116.5 15z"
              clip-rule="evenodd" />
          </svg>
        </div>


        <h2 class="my-8 text-2xl font-bold md:text-4xl">
          What is Kreyativ?
        </h2>
        <hr class="mb-10 border-gray-600 w-1/5" />
        <p>
          The goal of startup software development company is to do its best help humans with creative, original, innovative and beneficial protect improng globally. Kreyativ aims for originality and innovation
          in every project. The company embraces innovation and creativity and strives to use them in every project.
        </p>
        <p class="text-gray-300 block mt-8">Our company realizes all its business in accordance ethics values.</p>
      </div>

      <div
        class="text-gray-300 mt-16 grid text-base divide-x divide-y divide-gray-700 overflow-hidden rounded-3xl border border-gray-700 sm:grid-cols-2 lg:grid-cols-4 lg:divide-y-0 xl:grid-cols-4">
        <div class="group relative bg-gray-800 transition hover:z-[1] hover:shadow-2xl hover:shadow-gray-600/10">
          <div class="relative space-y-8 py-12 p-8">
            <img src="@/assets/icons/star.png" class="w-12" width="512" height="512" alt="burger illustration" />

            <div class="space-y-2">
              <h5 class="text-xl font-semibold transition group-hover:text-secondary">
                Original and Creative
              </h5>
              <p>
                The work principles of our company emphasizes originality and innovation.
              </p>
            </div>
            <span class="flex items-center justify-between group-hover:text-secondary">
              <img
                class="w-5 h-5 -translate-x-4 text-2xl opacity-0 transition duration-300 group-hover:translate-x-0 group-hover:opacity-100"
                src="@/assets/icons/Fishing.svg" alt="">
            </span>
          </div>
        </div>
        <div class="group relative bg-gray-800 transition hover:z-[1] hover:shadow-2xl hover:shadow-gray-600/10">
          <div class="relative space-y-8 py-12 p-8">
            <img src="@/assets/icons/open-source.png" class="w-12" width="512" height="512" alt="burger illustration" />

            <div class="space-y-2">
              <h5 class="text-xl font-semibold transition group-hover:text-secondary">
                Open Source
              </h5>
              <p>
                Through the open source projects we suggest free accessible technological solitons for everyone.
              </p>
            </div>
            <span class="flex items-center justify-between group-hover:text-secondary">
              <img
                class="w-5 h-5 -translate-x-4 text-2xl opacity-0 transition duration-300 group-hover:translate-x-0 group-hover:opacity-100"
                src="@/assets/icons/open-book.svg" alt="">
            </span>
          </div>
        </div>
        <div class="group relative bg-gray-800 transition hover:z-[1] hover:shadow-2xl hover:shadow-gray-600/10">
          <div class="relative space-y-8 py-12 p-8">
            <img src="@/assets/icons/shield.png" class="w-12" width="512" height="512" alt="burger illustration" />

            <div class="space-y-2">
              <h5 class="text-xl font-semibold transition group-hover:text-secondary">
                Privacy
              </h5>
              <p>
                We work on our platforms by giving utmost importance to your privacy and personal information.
              </p>
            </div>
            <span class="flex items-center justify-between group-hover:text-secondary">
              <img
                class="w-5 h-5 -translate-x-4 text-2xl opacity-0 transition duration-300 group-hover:translate-x-0 group-hover:opacity-100"
                src="@/assets/icons/privacy-policy.svg" alt="">
            </span>
          </div>
        </div>
        <div class="group relative bg-gray-900 transition hover:z-[1] hover:shadow-2xl hover:shadow-gray-600/10">
          <div class="relative space-y-8 py-12 p-8 transition duration-300 group-hover:bg-gray-800">
            <img src="@/assets/icons/friends.png" class="w-12" width="512" height="512" alt="burger illustration" />

            <div class="space-y-2">
              <h5 class="text-xl font-semibold transition group-hover:text-secondary">
                User Friendly
              </h5>
              <p>
                We work hard to provide our customers with a user-friendly experience. To do this, we use many different
                strategies and pay great attention to our customers' feedback.
              </p>
            </div>
            <span class="flex items-center justify-between group-hover:text-secondary">

              <img
                class="w-5 h-5 -translate-x-4 text-2xl opacity-0 transition duration-300 group-hover:translate-x-0 group-hover:opacity-100"
                src="@/assets/icons/user-crown.svg" alt="">
            </span>
          </div>
        </div>
      </div>
      <div class="text-lg w-full text-center">

        <h2 class="mt-48 text-2xl font-bold  md:text-4xl">
          We shape the future with our projects.
        </h2>
        <hr class="mx-auto mt-10 mb-16 border-gray-600 w-1/5" />
        <p>
          Kreyativ Software Development Company aims to provide innovative and creative technological solutions that add value to the world. Our vision is to develop projects that bring more convenience, efficiency, and satisfaction to people's daily lives. We strive to create new opportunities and experiences in the world of technology for everyone.
        </p>
        <p class="mt-5 text-gray-300">
          Kreyativ is a company firmly committed to its values. Innovation, quality, user-centricity, and sustainability are the core values of our work. Through innovation, we go beyond the ordinary and generate new ideas and solutions. Quality is a priority that we meticulously follow at every stage of our products. User-centricity is our guiding principle to understand the needs of users and place them at the center of our work.
        </p>
      </div>
    </div>
  </section>
</template>