<template>
  <section class="relative w-full py-16 bg-white" id="pricing">
    <div class="max-w-4xl px-10 mx-auto md:px-0">
      <h2 class="max-w-5xl mx-auto text-5xl font-black text-left text-gray-800 md:text-6xl md:text-center">
        Flexible Pricing Plans</h2>
      <p class="max-w-xl mx-auto my-10 text-base text-left text-gray-500 md:text-center">If you want
        to unlock our premium features and gain access to our pro tools, you may want to consider
        subscribing to one of our plans below.</p>
    </div>

    <div class="absolute bottom-0 left-0 w-full">
      <svg class="absolute bottom-0 w-full h-auto transform fill-current -translate-y-96 text-gray-50"
           viewBox="0 0 1440 139"
           xmlns="http://www.w3.org/2000/svg">
        <path d="M0 32l120 26.7C240 85 480 139 720 133.3 960 128 1200 64 1320 32l120-32v139H0V32z"></path>
      </svg>
      <div class="absolute top-0 bottom-0 w-full transform h-96 -translate-y-96 bg-gray-50"></div>
    </div>
    <div class="relative flex flex-col items-end w-full px-10 mx-auto space-x-10 md:max-w-3xl md:px-0 md:flex-row">
      <div class="w-full bg-white border rounded-lg shadow-xl border-gray-50 p-7 md:max-w-sm">
        <div class="flex flex-col pb-8 border-b border-gray-200">
          <h2 class="text-xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-purple-600">
            Monthly</h2>
          <p class="mt-2 text-sm leading-relaxed text-gray-600">Gain access to premium tools and
            upgrade your account with our monthly plan</p>
          <div class="flex items-end mt-4 space-x-2 text-xs">
            <h3 class="text-4xl font-bold text-transparent bg-clip-text bg-gradient-to-b from-blue-400 to-purple-600">
              $3</h3>
            <p class="mb-1 text-gray-400">per month</p>
          </div>
        </div>
        <landing-pricing-features></landing-pricing-features>

        <a href="#_"
           class="py-3.5 text-sm font-medium flex items-center justify-center bg-blue-600 hover:bg-blue-500 rounded-lg text-white">Select
          Plan</a>
      </div>

      <div class="w-full mt-10 bg-white border-2 border-gray-900 rounded-lg shadow-xl md:mt-0 md:max-w-sm">
        <div class="flex items-center justify-center py-2 text-sm font-semibold text-white bg-gray-900">
          Most popular choice
        </div>
        <div class="p-7">
          <div class="flex flex-col pb-8 border-b border-gray-200">
            <h2 class="text-xl font-bold text-gray-900">Yearly</h2>
            <p class="mt-2 text-sm leading-relaxed text-gray-600">Gain access to premium tools and
              upgrade your account with our yearly plan</p>
            <div class="flex items-end mt-4 space-x-2 text-xs">
              <h3 class="text-4xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-gray-600 to-black">
                $30</h3>
              <p class="mb-1 text-gray-400">per year</p>
            </div>
          </div>
          <landing-pricing-features></landing-pricing-features>

          <a href="#_"
             class="py-3.5 text-sm font-medium flex items-center justify-center bg-gray-900 hover:bg-gray-800  to-black rounded-md text-white">Select
            Plan</a>
        </div>
      </div>

    </div>
  </section>
</template>
