<template lang="pug">
article
  nuxt-content(:document="article")
  pre {{ article }}
</template>

<script>
export default {
  async asyncData({ $content, params }) {
    // fetch our article here
    const article = await $content("blog", params.slug).fetch();

    return { article };
  },
};
</script>
