<template>
  <div
    class="bg-gradient-to-b from-black to-n-mBlue"
    :class="{ 'h-screen': elementVisible }"
  >
    <OrganismPageLoader />
    <a href="#content" class="sr-only text-blue-600 focus:not-sr-only">
      Skip to main content
    </a>
    <AtomIeBanner />
    <div class="">
      <OrganismHeader />
      <div id="content" />
      <slot />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      elementVisible: true,
    };
  },

  mounted() {
    setTimeout(() => {
      this.elementVisible = false;
    }, 2000);
  },
};
</script>
