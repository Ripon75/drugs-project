<template>
  <WebDefaultLayout>
  <PageHeader pageTitle="Contact Us" bgImageSRC="/images/banners/banner-contact.jpg"></PageHeader>

    <section class="container mx-auto page-section">
      <section class="text-gray-600 body-font relative">
        <div class="mx-auto flex sm:flex-nowrap flex-wrap">
          <div data-aos="fade-right" class="lg:w-2/3 md:w-full bg-gray-300 rounded-lg overflow-hidden sm:mr-10 p-10 flex items-end justify-start relative">
            <iframe width="100%" height="100%" class="absolute inset-0" frameborder="0" title="map" marginheight="0" marginwidth="0" scrolling="no"
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3652.368098215265!2d90.40477953543605!3d23.73424956850221!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755b8f3edff3faf%3A0x66efe1e47ad1a710!2s31%20Segun%20Bagicha%20Rd%2C%20Dhaka%201000!5e0!3m2!1sen!2sbd!4v1642482619040!5m2!1sen!2sbd"
              style="filter: grayscale(0.0) contrast(1) opacity(0.8);">
            </iframe>
            <div class="bg-white relative flex flex-wrap py-6 rounded shadow-xl">
              <div class="lg:w-1/2 px-6">
                <h2 class="title-font font-bold text-gray-900 tracking-widest text-base">ADDRESS</h2>
                <p class="mt-1">31 Segunbagicha, Dhaka 1000, Bangladesh</p>
                <h2 class="title-font font-bold text-gray-900 tracking-widest text-base mt-4">HOTLINE</h2>
                <p class="leading-relaxed font-semibold">+88 01322 800 600</p>
              </div>
              <div class="lg:w-1/2 px-6 mt-4 lg:mt-0">
                <h2 class="title-font font-bold text-gray-900 tracking-widest text-base">EMAIL</h2>
                <a class="text-indigo-500 leading-relaxed">info@technodrugsltd.com</a>
                <h2 class="title-font font-bold text-gray-900 tracking-widest text-base mt-4">PHONE</h2>
                <p class="leading-relaxed font-semibold">+88 02-835-6037</p>
              </div>
            </div>
          </div>
          <div data-aos="fade-left" class="lg:w-1/3 md:w-1/2 bg-white flex flex-col md:ml-auto w-full md:py-8 mt-8 md:mt-0">
            <h2 class="text-gray-900 text-xl mb-1 font-bold title-font">Feedback</h2>
            <div class="relative mb-4">
              <label for="name" class="leading-7 text-sm text-gray-600">Name</label>
              <input type="text" id="name" name="name" class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
            </div>
            <div class="relative mb-4">
              <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
              <input type="email" id="email" name="email" class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
            </div>
            <div class="relative mb-4">
              <label for="message" class="leading-7 text-sm text-gray-600">Message</label>
              <textarea id="message" name="message" class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"></textarea>
            </div>
            <button class="text-white bg-black border-0 py-2 px-6 focus:outline-none hover:bg-primary rounded text-lg">Send</button>
          </div>
        </div>
      </section>
    </section>
  </WebDefaultLayout>
</template>

<script>
  import WebDefaultLayout from '@/Layouts/WebDefaultLayout.vue'
  import PageHeader from '@/Layouts/Components/PageHeader.vue'
  import AOS from 'aos'
  import 'aos/dist/aos.css'

  export default {
    components: {
      WebDefaultLayout,
      PageHeader
    },
    created () {
        AOS.init()
    },

  }
</script>

<style>

</style>
