<template>
  <section class="text-xs  border border-black pb-3">
    <img src="../assets/img/tourism.png" class="mb-2 w-[24.375rem] h-[6.25rem]" />
    <h4 class="text-sm font-bold text-ruri ">{{ advertisingCard.title }}</h4>
    <p class="px-2 text-font">
      {{ advertisingCard.content }}
    </p>
  </section>
</template>
<script>
export default {
  props: { advertisingCard: Object }
};
</script>
