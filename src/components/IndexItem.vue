<script setup lang="ts">
import IconGithub from './icons/IconGithub.vue'
import IconSpotify from './icons/IconSpotify.vue'
import IconTelegram from './icons/IconTelegram.vue'
import IconVkontakte from './icons/IconVkontakte.vue'
</script>

<template>
  <div class="container">
    <div class="center-block">
      <p class="pretext">Это я</p>
      <h1 class="main-header">XlynxX</h1>
      <div class="social-block">
        <a class="social-container neu-button-rounded" href="https://vk.com/xlynxx1" target="_blank">
          <IconVkontakte class=""></IconVkontakte>
        </a>
        <a class="social-container neu-button-rounded" href="https://t.me/XlynxX1" target="_blank">
          <IconTelegram class=""></IconTelegram>
        </a>
        <a class="social-container neu-button-rounded" href="https://github.com/XlynxX" target="_blank">
          <IconGithub class=""></IconGithub>
        </a>
        <a class="social-container neu-button-rounded"
          href="https://open.spotify.com/user/31nmaymu24kg2kgaus4x6xplc7di?si=df331008cb9b4a48" target="_blank">
          <IconSpotify class=""></IconSpotify>
        </a>
      </div>
      <div hidden>
        <p>{linkText}</p>
      </div>
      <div class="neu-flat articles-block">
        <a href="/projects" class="neu-button">проекты</a>
        <a href="/articles" class="neu-button">статьи</a>
        <a href="/about" class="neu-button">обо мне</a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  height: 100svh;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  align-content: space-between;
  justify-content: space-evenly;
  align-items: center;
}

.articles-block {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 1.6rem;
  animation: divPlayed;
  animation-duration: 2s;
  margin-top: 2.2rem;
}

.social-block {
  justify-content: center;
  animation: divPlayed;
  animation-duration: 1.7s;
  width: 100%;
  display: flex;
}

.social-container {
  display: inline-block;
  width: 50px;
  height: 50px;
  position: relative;
  overflow: hidden;
  vertical-align: middle;
  margin: 0.3rem 0.6rem 0.3rem 0.6rem;
}

.pretext {
  font-size: 12px;
  animation: divPlayed;
  animation-duration: 1s;
  font-weight: 200;
}

.main-header {
  font-size: 56px;
  animation: divPlayed;
  animation-duration: 1.3s;
  font-weight: 200;
  margin-top: -8px;
  margin-bottom: 0.5rem;
  line-height: 1.2;
}

.center-block {
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: center;
  align-items: center;
  padding: 0.3rem;
}
</style>
