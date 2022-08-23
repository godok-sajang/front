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
* {
  box-sizing: border-box;
}

#app {
  font-family: Noto Sans KR, sans-serif, BMYeonSung;
}

html {
  color: #000000;
  line-height: 1.4;
}

html, body, #app {
  height: 100%;
}

button {
  border: none;
  background: none;
  cursor: pointer;
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
