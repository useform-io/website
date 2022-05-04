<template>
  <section class="text-gray-900 bg-gray-900 box-border">
    <div class="py-12 leading-7 md:pt-24 md:pb-20 box-border">
      <div class="relative px-10 md:px-5 mx-auto w-full text-gray-900">
        <div class="flex flex-wrap justify-center mt-0">
          <div class="relative flex-none mb-16 lg:mb-24 px-5 mt-0 w-full max-w-full text-center md:w-5/6 md:flex-none lg:w-2/3 lg:flex-none">
            <h6 class="mt-0 mb-2 text-xs font-normal tracking-widest text-yellow-200 uppercase">
              Integrations</h6>
            <h1 class="mt-0 mb-4 text-4xl font-semibold tracking-normal text-white">Works with
              your favorite services</h1>
            <p class="mt-0 text-lg leading-8 text-gray-400">We've built some seamless integrations
              with some of the industries favorite tools and services.</p>
          </div>
        </div>
        <!-- Start of integration list -->
        <div class="flex flex-wrap mt-0 max-w-6xl mx-auto">
          <landing-integrations-item label="Slack"
                                     description="Setup Slack notifications and alerts anytime your form was submitted.">
            <svg class="w-12 h-12 mx-auto"
                 viewBox="0 0 412 412"
                 xmlns="http://www.w3.org/2000/svg">
              <g fill-rule="nonzero" fill="none">
                <path d="M281 296c11-26-4-38-19-38l-148-2c-4 0-4-6 1-7l150-2c17-1 37-15 43-33 0 0 10-21 9-24-8.9-42.943-45.506-74.572-89.285-77.147-43.78-2.575-83.842 24.544-97.715 66.147-38-25-78 9-69 46-48 3-65 46-60 72 0 1 1 2 3 2h274c1 0 3-1 3-3Z"
                      fill="#F38020"
                      class=""></path>
                <path d="M331 194c-4 0-6-1-7 1l-5 21c-5 16 3 30 20 31l32 2c4 0 4 6-1 7l-33 1c-36 4-46 39-46 39 0 2 0 3 2 3h113l3-2a81 81 0 0 0-78-103"
                      fill="#FAAE40"></path>
              </g>
            </svg>
          </landing-integrations-item>
        </div>
      </div>
    </div>
    <div class="relative py-8 px-10 md:px-5 mx-auto w-full text-gray-900 border-gray-800 max-w-6xl border-t md:py-20"
         style="z-index: 1;">
      <div class="flex md:flex-row flex-col justify-between items-center">
        <div class="relative flex-none px-5 md:flex-shrink-0">
          <h3 class="mt-0 mb-1 text-xl font-semibold tracking-normal text-white box-border"
              style="line-height: 1.4;"> Want to build a custom integration? </h3>
          <p class="mt-0 mb-6 text-lg leading-8 md:mb-0 box-border text-gray-400"> Request an
            integration or build your own. </p>
        </div>
        <div class="relative flex-shrink-0 px-5">
          <a href="#"
             class="inline-block py-3 px-5 text-base font-semibold text-center text-white align-middle bg-blue-600 rounded-md border border-transparent border-solid cursor-pointer select-none box-border hover:border-blue-800 hover:bg-blue-700 hover:text-white focus:border-blue-800 focus:bg-blue-700 focus:text-white">Get
            Started</a>
        </div>
      </div>
    </div>
  </section>
</template>

