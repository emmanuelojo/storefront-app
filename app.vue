<!-- <template>
  <div>
    <NuxtWelcome />
  </div>
</template> -->

<template>
    <div class="flex flex-col items-center space-y-4 xs:block xs:space-x-4">
        <GsButton type="button" variant="primary"> Hello </GsButton>
        <GsButton type="button" variant="secondary"> Hello </GsButton>
        <GsButton type="button" variant="tertiary"> Hello </GsButton>

        <product-card-vertical />
    </div>
</template>

<script lang="ts" setup>
// import { SfButton } from "@storefront-ui/vue";
</script>
