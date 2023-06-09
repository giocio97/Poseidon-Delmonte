<template>
    <div class="progress-bar">
        <div class="progress-inner" :style="`width:${progress}%`"></div>
    </div>
</template>
  
<script>
export default {
    name: 'ProgressBar',
    props: ['progress']

}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
//  progress Bar 
.progress-bar {
    width: 100%;
    height: 20px;
    background-color: #fff;
    position: fixed;
    bottom: 0;

    .progress-inner {
        background-image: linear-gradient(to top, #4481eb 0%, #04befe 100%);
        height: 100%;

        border-radius: 0 10px 10px 0;
    }




}
</style>
  