<template>
  <div>
    <h1>Common Page with <span class="text-blue-500">common</span> layout</h1>
    <FormWow />
    <div class="flex md:gap-x-5 px-5">
      <Card
        :imgSrc="'https://images.unsplash.com/photo-1453728013993-6d66e9c9123a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8dmlld3xlbnwwfHwwfHw%3D&w=1000&q=80'"
        :title="'hello'"
        :description="'Card description will goes here'"
        :btnName="'first button'"
      />
      <Card
        imgSrc="https://images.unsplash.com/photo-1453728013993-6d66e9c9123a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8dmlld3xlbnwwfHwwfHw%3D&w=1000&q=80"
        :title="'hello2'"
        :description="'Card description will goes here2'"
        :btnName="'second button'"
      />
      <Card
        imgSrc="https://images.unsplash.com/photo-1453728013993-6d66e9c9123a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8dmlld3xlbnwwfHwwfHw%3D&w=1000&q=80"
        :title="'hello3'"
        :description="'Card description will goes here3'"
        :btnName="'third button'"
      />
    </div>
    <NuxtLink to="/about" class="border bg-gray-200 px-4 py-1 text-red-600"
      >go somewhere</NuxtLink
    >
  </div>
</template>

<script setup></script>
