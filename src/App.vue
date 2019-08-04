<template>
  <div id="app">
    <Title value="Flappy Bird"/>
    <Flappy>
      <Bird />
      <PipeArea>
        
      </PipeArea>
      <Progress />
    </Flappy>
  </div>
</template>

<script>
import Title from './components/Title'
import Flappy from './components/Flappy'
import Progress from './components/Progress'
import Bird from './components/Bird'
import PipeArea from './components/PipeArea'

export default {
  name: 'App',
  components: {
    Title, Flappy, Progress, Bird, PipeArea
  }
}
</script>

<style>
  @font-face {
    font-family: 'Oswald';
    src: url('assets/fonts/Oswald-Regular.ttf') format('truetype');
  }

  * {
      font-family: 'Oswald', sans-serif;
  }

  html {
      height: 100%;
  }

  body {
      margin: 0;
      background-color: #0D262D;
      color: #fff;
      height: 100%;
  }

  #app {
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100%;
  }
</style>
