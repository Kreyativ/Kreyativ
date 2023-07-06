<template>
   <section style="margin: 0;" class="flex relative px-4 mx-auto md:max-w-full lg:h-screen max-sm:px-2 max-md:px-20 lg:px-8 py-40">
    <div aria-hidden="true" class="absolute inset-0 grid grid-cols-2 -space-x-52 opacity-20">
        <div class="blur-[106px] h-56 bg-gradient-to-br from-primaryfrom-blue-700"></div>
        <div class="blur-[106px] h-32 bg-gradient-to-r from-cyan-400 to-indigo-600"></div>
    </div>
  <div class="grid items-center gap-10 z-10 mx-auto lg:grid-cols-2">
    <div class="lg:pr-10 text-gray-300">
      <h5 class="cool mb-4 text-5xl font-extrabold leading-none">
        Kreyativ Software<br class="hidden md:block" />
         <span class="inline-block text-blue-500 ">Development</span> Company.
      </h5>
      <p class="mb-6">
        We try to benefit you with our original and innovative  projects.
      </p>
      <hr class="mb-5 border-gray-600" />
      <div class="gap-4 flex items-center space-x-4">
          <a class="btn" href="https://blog.kreyativ.co/contact">
            contact
          </a>
        <a target="_blank" href="https://www.youtube.com/channel/UCVYLYcLRcMXQqtA0An1gjOQ" class="animate-border transition-all p-4 flex gap-2 items-center">
          watch
          <img src="@/assets/icons/play.svg" alt="">
        </a>
      </div>
    </div>
    <div class="relative mx-auto max-lg:-order-1">
      <div class="w-96 rounded-full h-96 aspect-square z-[-1] absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2
 blur-[8rem] bg-[radial-gradient(ellipse_at_center,_var(--tw-gradient-stops))] from-blue-900 to-sky-600 animate-pulse"></div>
      <svg width="80%" height="100%" class="max-lg:w-8/12 max-md:w-7/12 mx-auto" viewBox="0 0 814 1717" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M365 432.5V74L29 432.5V739H365H533V1113H622" stroke="#EFEFEF" stroke-width="58" class="svg-elem-1"></path>
          <path d="M449 1284.5V1643L785 1284.5V978H449H281V604H192" stroke="#EFEFEF" stroke-width="58" class="svg-elem-2"></path>
      </svg>
    </div>
  </div>
</section>
</template>


<style scoped>

svg {
  color: #bbb
}
div {
  @apply text-gray-300
}

button {
  color: #ececec!important
}
img.w-96:hover {

}
 @-webkit-keyframes animate-svg-stroke-1 {
  0% {
    stroke-dashoffset: 2125.34326171875px;
    stroke-dasharray: 2125.34326171875px;
  }

  100% {
    stroke-dashoffset: 0;
    stroke-dasharray: 2125.34326171875px;
  }
}

@keyframes animate-svg-stroke-1 {
  0% {
    stroke-dashoffset: 2125.34326171875px;
    stroke-dasharray: 2125.34326171875px;
  }

  100% {
    stroke-dashoffset: 0;
    stroke-dasharray: 2125.34326171875px;
  }
}

.svg-elem-1 {
  -webkit-animation: animate-svg-stroke-1 1s linear 0s both;
          animation: animate-svg-stroke-1 1s linear 0s both;
}

@-webkit-keyframes animate-svg-stroke-2 {
  0% {
    stroke-dashoffset: 2125.34326171875px;
    stroke-dasharray: 2125.34326171875px;
  }

  100% {
    stroke-dashoffset: 0;
    stroke-dasharray: 2125.34326171875px;
  }
}

@keyframes animate-svg-stroke-2 {
  0% {
    stroke-dashoffset: 2125.34326171875px;
    stroke-dasharray: 2125.34326171875px;
  }

  100% {
    stroke-dashoffset: 0;
    stroke-dasharray: 2125.34326171875px;
  }
}

.svg-elem-2 {
  -webkit-animation: animate-svg-stroke-2 1s linear 0.12s both;
          animation: animate-svg-stroke-2 1s linear 0.12s both;
}
.animate-border {
  background-image: conic-gradient(from var(--border-angle), #213, #112 50%, #213), conic-gradient(from var(--border-angle), transparent 20%, #08f, #f03);
  background-size: calc(100% - (var(--border-size) * 2)) calc(100% - (var(--border-size) * 2)), cover;
  background-position: center center;
  background-repeat: no-repeat;
  -webkit-animation: bg-spin 3s linear infinite;
          animation: bg-spin 3s linear infinite;
          --border-size: 3px;
  --border-angle: 0turn;
}
.animate-border:hover {
  animation-play-state: paused;
  opacity: 75%;
}
@-webkit-keyframes bg-spin {
  to {
    --border-angle: 1turn;
  }
}
@keyframes bg-spin {
  to {
    --border-angle: 1turn;
  }
}
@property --border-angle {
  syntax: "<angle>";
  inherits: true;
  initial-value: 0turn;
}
</style>