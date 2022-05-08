<template>
  <section class="box-border relative overflow-hidden w-full font-sans leading-6 text-gray-700 bg-white border-0 border-gray-200 border-solid"
           id="features">
    <div class="box-border flex flex-col items-center px-8 py-20 mx-auto leading-6 border-solid max-w-7xl xl:px-16 md:items-stretch md:justify-center md:py-24">
      <div class="relative pb-10">
        <h5 class="w-full mx-0 mt-0 mb-4 font-sans font-bold text-center text-purple-700 border-0 border-gray-200">
          Features
        </h5>
        <h2 class="w-full m-0 font-sans text-4xl font-black  tracking-wide text-center text-gray-700 border-0 border-gray-200 sm:text-5xl">
          Amazing Features
        </h2>
        <p class="w-full max-w-xl mx-auto mt-4 mb-0 font-sans text-sm font-medium leading-relaxed text-center text-gray-400 border-0 border-gray-200 lg:text-lg md:text-base">
          Check out our set of awesome features and tools. We are the industry leaders in providing
          quality tools, trusted and used by over 1,200 companies. We kind'of rock!
        </p>
      </div>

      <div class="z-10 grid gap-5 md:grid-cols-6 lg:grid-cols-9">
        <!-- Feature 1 -->
        <div class="col-span-3 font-sans text-gray-700 bg-gray-50 rounded-3xl">
          <div class="box-border flex flex-col items-start h-full px-2 py-8 mx-4 leading-6 text-center border-solid sm:flex-row sm:items-start sm:text-left">
            <div class="flex-shrink-0 p-3 font-sans text-gray-700 border border-gray-200 rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg"
                   class="leading-6 text-center text-gray-700 align-middle stroke-current w-7 h-7"
                   viewBox="0 0 24 24"
                   stroke-width="1.5"
                   stroke="#2c3e50"
                   fill="none"
                   stroke-linecap="round"
                   stroke-linejoin="round">
                <path d="M0 0h24v24H0z" stroke="none"></path>
                <path d="M12 3l8 4.5v9L12 21l-8-4.5v-9L12 3M12 12l8-4.5M12 12v9M12 12L4 7.5M16 5.25l-8 4.5"></path>
              </svg>
            </div>
            <div class="mt-4 font-sans text-left text-gray-700 border-0 border-gray-200 sm:mt-2 sm:ml-4">
              <h6 class="box-border text-2xl font-bold leading-none tracking-wide text-left border-solid">
                Zero-backend</h6>
              <p class="box-border mx-0 mt-1 mb-0 font-medium leading-loose text-gray-400 border-solid sm:mt-4">
                No server or backend developer needed, just copy-n-paste form endpoint and go live.
              </p>
            </div>
          </div>
        </div>
        <!-- Feature 2 -->
        <div class="col-span-3 font-sans text-gray-700 bg-gray-50 rounded-3xl">
          <div class="box-border flex flex-col items-start h-full px-2 py-8 mx-4 leading-6 text-center border-solid sm:flex-row sm:items-start sm:text-left">
            <div class="flex-shrink-0 p-3 font-sans text-gray-700 border border-gray-200 rounded-full">

              <svg xmlns="http://www.w3.org/2000/svg"
                   class="h-6 w-6"
                   fill="none"
                   viewBox="0 0 24 24"
                   stroke="currentColor"
                   stroke-width="2">
                <path stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/>
              </svg>

            </div>
            <div class="mt-4 font-sans text-left text-gray-700 border-0 border-gray-200 sm:mt-2 sm:ml-4">
              <h6 class="box-border text-2xl font-bold leading-none tracking-wide text-left border-solid">
                Protected</h6>
              <p class="box-border mx-0 mt-1 mb-0 font-medium leading-loose text-gray-400 border-solid sm:mt-4">
                Forget about spam with our Spam Filters and Google Recaptcha out of the box.
              </p>
            </div>
          </div>
        </div>
        <div class="col-span-3 font-sans text-gray-700 bg-gray-50 rounded-3xl">
          <div class="box-border flex flex-col items-start h-full px-2 py-8 mx-4 leading-6 text-center border-solid sm:flex-row sm:items-start sm:text-left">
            <div class="flex-shrink-0 p-3 font-sans text-gray-700 border border-gray-200 rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg"
                   class="h-6 w-6"
                   fill="none"
                   viewBox="0 0 24 24"
                   stroke="currentColor"
                   stroke-width="2">
                <path stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 10h18M3 14h18m-9-4v8m-7 0h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z"/>
              </svg>
            </div>
            <div class="mt-4 font-sans text-left text-gray-700 border-0 border-gray-200 sm:mt-2 sm:ml-4">
              <h6 class="box-border text-2xl font-bold leading-none tracking-wide text-left border-solid">
                Analyse</h6>
              <p class="box-border mx-0 mt-1 mb-0 font-medium leading-loose text-gray-400 border-solid sm:mt-4">
                Export all your submissions to CSV or Excel formats easily with one button press.
              </p>
            </div>
          </div>
        </div>
        <div class="col-span-3 font-sans text-gray-700 bg-gray-50 rounded-3xl">
          <div class="box-border flex flex-col items-start h-full px-2 py-8 mx-4 leading-6 text-center border-solid sm:flex-row sm:items-start sm:text-left">
            <div class="flex-shrink-0 p-3 font-sans text-gray-700 border border-gray-200 rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg"
                   class="leading-6 text-center text-gray-700 align-middle stroke-current w-7 h-7"
                   width="44"
                   height="44"
                   viewBox="0 0 24 24"
                   stroke-width="1.5"
                   stroke="#2c3e50"
                   fill="none"
                   stroke-linecap="round"
                   stroke-linejoin="round">
                <path d="M0 0h24v24H0z" stroke="none"></path>
                <path d="M3 12h3M12 3v3M7.8 7.8L5.6 5.6M16.2 7.8l2.2-2.2M7.8 16.2l-2.2 2.2M12 12l9 3-4 2-2 4-3-9"></path>
              </svg>
            </div>
            <div class="mt-4 font-sans text-left text-gray-700 border-0 border-gray-200 sm:mt-2 sm:ml-4">
              <h6 class="box-border text-2xl font-bold leading-none tracking-wide text-left border-solid">
                Simple</h6>
              <p class="box-border mx-0 mt-1 mb-0 font-medium leading-loose text-gray-400 border-solid sm:mt-4">
                We've built one of the simplest tools to integrate into your current system.
              </p>
            </div>
          </div>
        </div>
        <div class="col-span-3 font-sans text-gray-700 bg-gray-50 rounded-3xl">
          <div class="box-border flex flex-col items-start h-full px-2 py-8 mx-4 leading-6 text-center border-solid sm:flex-row sm:items-start sm:text-left">
            <div class="flex-shrink-0 p-3 font-sans text-gray-700 border border-gray-200 rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg"
                   class="h-6 w-6"
                   fill="none"
                   viewBox="0 0 24 24"
                   stroke="currentColor"
                   stroke-width="2">
                <path stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M3 15a4 4 0 004 4h9a5 5 0 10-.1-9.999 5.002 5.002 0 10-9.78 2.096A4.001 4.001 0 003 15z"/>
              </svg>
            </div>
            <div class="mt-4 font-sans text-left text-gray-700 border-0 border-gray-200 sm:mt-2 sm:ml-4">
              <h6 class="box-border text-2xl font-bold leading-none tracking-wide text-left border-solid">
                Cloud based</h6>
              <p class="box-border mx-0 mt-1 mb-0 font-medium leading-loose text-gray-400 border-solid sm:mt-4">
                We have the fastest response times than any other service in our industry.
              </p>
            </div>
          </div>
        </div>
        <div class="col-span-3 font-sans text-gray-700 border-0 bg-gray-50 rounded-3xl">
          <div class="box-border flex flex-col items-start h-full px-2 py-8 mx-4 leading-6 text-center border-solid sm:flex-row sm:items-start sm:text-left">
            <div class="flex-shrink-0 p-3 font-sans text-gray-700 border border-gray-200 rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg"
                   class="leading-6 text-center text-gray-700 align-middle stroke-current w-7 h-7"
                   width="44"
                   height="44"
                   viewBox="0 0 24 24"
                   stroke-width="1.5"
                   stroke="#2c3e50"
                   fill="none"
                   stroke-linecap="round"
                   stroke-linejoin="round">
                <path d="M0 0h24v24H0z" stroke="none"></path>
                <rect x="3" y="4" width="18" height="8" rx="3"></rect>
                <rect x="3" y="12" width="18" height="8" rx="3"></rect>
                <path d="M7 8v.01M7 16v.01"></path>
              </svg>

            </div>
            <div class="mt-4 font-sans text-left text-gray-700 border-0 border-gray-200 sm:mt-2 sm:ml-4">
              <h6 class="box-border text-2xl font-bold leading-none tracking-wide text-left border-solid">
                Reliable</h6>
              <p class="box-border mx-0 mt-1 mb-0 font-medium leading-loose text-gray-400 border-solid sm:mt-4">
                We pride ourselves in our up-time metrics. We focus a lot of our energy on being
                reliable.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>


    <div class="absolute top-0 left-0 -ml-56 opacity-25 w-96 h-96">
      <svg class="text-pink-500 opacity-50 fill-current w-88 h-88"
           viewBox="0 0 200 200"
           xmlns="http://www.w3.org/2000/svg">
        <path d="M25.5,-24.7C35.8,-15.2,48.9,-7.6,50.6,1.7C52.3,11,42.6,22,32.3,31.2C22,40.4,11,47.8,-1.9,49.8C-14.9,51.7,-29.7,48.1,-41.1,38.9C-52.5,29.7,-60.5,14.9,-60.3,0.3C-60,-14.3,-51.5,-28.6,-40,-38.1C-28.6,-47.6,-14.3,-52.3,-3.4,-48.9C7.6,-45.5,15.2,-34.2,25.5,-24.7Z"
              transform="translate(100 100)"></path>
      </svg>
    </div>
    <div class="absolute top-0 right-0 -mb-56 opacity-25 w-96 h-96 -mr-72">
      <svg class="w-full h-full text-yellow-500 opacity-50 fill-current"
           viewBox="0 0 200 200"
           xmlns="http://www.w3.org/2000/svg">
        <path d="M44.3,-48.3C55.3,-33.4,60.4,-16.7,62.2,1.8C64,20.3,62.5,40.6,51.6,55.3C40.6,70,20.3,79,2.3,76.7C-15.7,74.4,-31.4,60.7,-46.7,46C-62,31.4,-76.9,15.7,-78.5,-1.6C-80,-18.8,-68.2,-37.6,-52.9,-52.5C-37.6,-67.5,-18.8,-78.5,-1.1,-77.5C16.7,-76.4,33.4,-63.3,44.3,-48.3Z"
              transform="translate(100 100)"></path>
      </svg>
    </div>

  </section>
</template>
