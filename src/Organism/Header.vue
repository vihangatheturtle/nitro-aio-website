<template>
  <header class="mx-auto flex max-w-8xl items-center justify-between px-6 pt-6">
    <g-link to="/" class="w-48 xl:w-56">
      <g-image src="~/images/full-logo.svg" immediate alt="" class="w-full" />
    </g-link>

    <div class="flex w-32 items-center justify-end space-x-4 xl:space-x-10">
      <AtomIconTwitter
        link="https://twitter.com/Nitro_AIO"
        class="text-n-lBlue hover:text-n-mBlue"
      />
      <AtomIconDiscord
        link="https://discord.gg/nitro-automation "
        class="text-n-lBlue hover:text-n-mBlue"
      />
    </div>
  </header>
</template>
