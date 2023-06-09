<template>
  <div id="app">
    <MyNavbar />
    <MyMain @progressUpdate="setProgress" />
    <ProgressBar :progress="progress" />
    <MyFooter />
  </div>
</template>

<script>
import MyNavbar from './components/MyNavbar.vue'
import MyMain from './components/MyMain.vue'
import ProgressBar from './components/ScrollBar.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyNavbar,
    MyMain,
    ProgressBar,
    MyFooter
  },
  data() {
    return {
      progress: 0
    }
  },
  methods: {
    setProgress(progress) {
      this.progress = progress;
    }
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

@import'~bootstrap/dist/css/bootstrap.css';
</style>
