<template>
  <div class="">
    <div class="w-full mx-auto px-4 sm:px-6 lg:px-8 xl:px-12 2xl:px-16">
      <h1
        class="invisible text-sky-300 text-9xl font-extrabold"
        v-gsap.from="{
          y: 20,
          autoAlpha: 0,
          duration: 0.8,
          ease: 'elastic.out(1, 0.3)'
        }"
      >
        About
      </h1>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
