<template>
  <HeaderComponent />
  <router-view class="router-view" />
</template>

<script>
import HeaderComponent from './components/layout/HeaderComponent.vue'
export default {
  components: { HeaderComponent },
}
</script>

<style lang="scss">
#app {
  font-family: Noto Sans KR, sans-serif, BMYeonSung;
}

html {
  height: 100%;
  color: #000000;
  line-height: 1.4;
}

input, button, textarea { font-family: inherit }

ol, ul, li {
  list-style: none;
}

@font-face {
  font-family: 'BMYeonSung';
  src: local('BMYeonSung'),
  url('@/assets/font/BMYeonSung.ttf') format("truetype"),
  url('@/assets/font/BMYeonSung.otf') format("opentype"),;
}

.router-view {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
