<template lang="pug">
.container
  div
    Logo
    h1.title
    | My static blog driven by nuxt.

    .links
      a.button--green(href='/blog/move-blog-to-nuxt' rel='noopener noreferrer')
        | Howto
      a.button--grey(href='https://github.com/ncwhale/blog.nuxt.js' target='_blank' rel='noopener noreferrer')
        | GitHub
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
