<template>
  <div
    class="
      h-screen
      flex
      flex-initial
      flex-col
      sm:flex-row
      justify-center
      items-center
      font-serif
      "
    >
    <img style="max-height: 50%" src="/rover-logo.png" />
    <!-- <nuxt-picture sizes="sm:100vw md:50vw lg:400px" src="/rover-logo.png" /> -->
    <div class="flex flex-col gap-3 m-10 bg-link text-white rounded p-3 shadow-2xl">
      <h1 class="text-3xl whitespace-nowrap">Rover Excavation</h1>
      <hr />
      <div class="italic">"We can dig it!"</div>
      <div>Jason: <a class="rounded p-1" href="tel:208-709-8676">208-709-8676</a></div>
      <div>Steven: <a class="rounded p-1" href="tel:208-313-5845">208-313-5845</a></div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
