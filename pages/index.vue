<template>
  <div>
    <h2>Home</h2>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Possimus, fugiat
      provident. Fuga officia, sit harum perspiciatis nulla molestias, neque
      quod dolores at maiores nihil sed beatae iure a enim. Soluta!
    </p>
  </div>
</template>

<script setup>
useHead({
  title: "Nuxt Dojo | Merch Store",
  meta: [
    {
      name: "description",
      content: "This is a merch store built with Nuxt.js and Tailwind CSS.",
    },
  ],
});
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}

p {
  margin: 20px 0;
}
</style>
