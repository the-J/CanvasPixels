<template>
    <MainContainer>
      <Toolbar />
      <Canvas />
    </MainContainer>
</template>

<script>
    import Canvas from '~/components/Canvas/Canvas.vue'
    import MainContainer from '~/components/MainContainer/MainContainer.vue'
    import Toolbar from '~/components/Toolbar/Toolbar.vue'


    export default {
        components: {
            Canvas,
            MainContainer,
            Toolbar
        }
    }
</script>

<style src="../components/pages/index.css"></style>
