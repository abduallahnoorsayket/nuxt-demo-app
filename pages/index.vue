<template>
  <div>
    <hr />
    <nuxt-mountains />
    <hr />
    <mountain-list />
    <hr />
    <NuxtLink to="/about">About page</NuxtLink>
    <hr />
    <NuxtLink to="/user">User page</NuxtLink>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
