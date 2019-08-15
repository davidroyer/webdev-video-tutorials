<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        Nuxt Demo
      </h1>
      <h2>Vimeo</h2>
      <iframe
        src="https://player.vimeo.com/video/101059360"
        width="640"
        height="361"
        frameborder="0"
        allow="autoplay; fullscreen"
        allowfullscreen
      ></iframe>
      <hr class="vid-seperator" />
      <iframe
        src="https://player.vimeo.com/video/353923621"
        width="640"
        height="400"
        frameborder="0"
        allow="autoplay; fullscreen"
        allowfullscreen
      ></iframe>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
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
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
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

.vid-seperator {
  padding: 2em;
  margin-top: 4em;
}
</style>
