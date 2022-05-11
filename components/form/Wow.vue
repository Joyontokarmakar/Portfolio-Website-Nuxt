<template>
  <form  class="border bg-gray-100 p-8">
    <div>
      <label for="name">Name</label> <br />
      <input id="name" v-model="formUpload.name" type="text" class="border" />
    </div>
    <div>
      <label for="email">Email</label> <br />
      <input id="email" v-model="formUpload.email" type="email" class="border" />
    </div>
    <div>
      <label for="password">Password</label> <br />
      <input id="password" v-model="formUpload.password" type="password" class="border" />
    </div>
    <input type="submit" name="Submit" class="border" />
  </form>
  {{ formUpload }}
</template>

<script setup>
let formUpload = ref({
  name: "",
  email: "",
  password: "",
});
</script>

<style></style>
