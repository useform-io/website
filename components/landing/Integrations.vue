<template>
  <section class="py-12 sm:py-16 bg-white" id="integrations">
    <div class="max-w-7xl px-10 mx-auto sm:text-center">
      <p class="text-blue-500 font-medium uppercase">Our Application Integrations</p>
      <h2 class="font-bold text-3xl sm:text-4xl lg:text-5xl mt-3">Connect with Your Favorite
        Apps.</h2>
      <p class="mt-4 text-gray-500 text-base sm:text-xl lg:text-2xl">We've built integrations with
        some of your favorite services.<br class="lg:hidden hidden sm:block"> Check'em out below 👇
      </p>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-10 my-12 sm:my-16">
        <landing-integrations-slack></landing-integrations-slack>
        <landing-integrations-telegram></landing-integrations-telegram>
        <landing-integrations-discord></landing-integrations-discord>
        <landing-integrations-webhooks></landing-integrations-webhooks>
        <landing-integrations-airtable></landing-integrations-airtable>
        <landing-integrations-google-sheets></landing-integrations-google-sheets>
        <landing-integrations-zapier></landing-integrations-zapier>
        <landing-integrations-mailchimp></landing-integrations-mailchimp>
      </div>
    </div>
  </section>
</template>

