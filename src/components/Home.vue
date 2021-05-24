<template>
  <div >
    <header class="container mx-auto flex p-5 items-center">
      <div class="container flex   justify-between items-center">
        <a class=" flex flex-wrap items-center justify-center">
          <h1 class="sm:text-2xl text-1xl py-2 font-medium">Raslan Ismail</h1>
        </a>

        <div class="md:ml-auto flex  items-center  justify-center">
          <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Hire Me</button>

        </div>

      </div>
    </header>

    <section class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
      <div class="container flex md:flex-row flex-col-reverse ">
        <div class="lg:flex-grow md:w-3/5 rounded-2xl mr-6 flex flex-col md:items-start md:text-left m-5 md:mb-0 border border-1 p-5">
          <p class="text-sm text-blue-400">Hello I am</p>
          <h3 class="text-2xl">Raslan Ismail</h3>
          <p class="mt-2 text-md ">I finished my Training since summer 2020 in Bremen,
            Germany and since then I am doing freelancing and focusing on learning new technologies everyday.
            I am listing all languages and Tools that I will be
            using in your Project down below. You Choose the Tools that you prefer or let me use Chose for you.</p>

          <h3 class="text-2xl mt-7">Tools & Languages</h3>
          <p class="mt-2">Java, Spring boot, Javascript(react, vuejs), Tailwindcss, Dart(Flutter)</p>

          <h3 class="text-1xl mt-7 font-bold">Contact Me:</h3>
          <p class="text-sm mt-1"> E-Mail: raslan.ismail87@gmail.com</p>
          <p class="text-sm mt-1">Mobile: 015780914756</p>

          <div class="flex w-full md:justify-start justify-center items-end">

          </div>

        </div>
        <div class=" md:w-2/5 p-5 md-p-0 mb-5">
          <img class="rounded-2xl" alt="Raslan" src="../assets/raslan.jpg">
        </div>
      </div>
    </section>

  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>
