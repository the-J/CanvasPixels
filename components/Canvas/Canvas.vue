<template>
  <canvas
    id="canvas"
    :width="width"
    :height="height" ></canvas>
</template>
<style src="./Canvas.css"></style>

<script>
  export default {
      data: function () {
          return {
              width: '500',
              height: '500'
          }
      }
  }
</script>
