<template>
  <div class="border bg-red-300 rounded-lg w-1/3 overflow-hidden">
    <img :src="imgSrc" alt="" class="w-full" />
    <div class="cardBody">
      <h1>{{ title }}</h1>
      <h1>{{ description }}</h1>
      <div class="cardFooter">
        <button
          class="rounded-lg bg-blue-50 bg-opacity-10 backdrop-blur-sm text-blue-500"
        >
          {{ btnName }}
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["imgSrc", "title", "description", "btnName"],
};
</script>

<style></style>
