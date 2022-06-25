<template>
  <div class="bg-gradient-to-b from-black to-n-mBlue">
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
