<template>
  <div>
    <post-card />
    <post-card />
    <post-card />
    <post-card />
    <post-card />
  </div>
</template>

<script>
import PostCard from "~/components/PostCard";
export default {
  data() {
    return {
      name: "nuxt",
    };
  },
  components: {
    PostCard,
  },
};
</script>

<style></style>
