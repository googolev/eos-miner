<template>
  <div class="home">
    <KeyConnectFrom />
  </div>
</template>

<script>
import KeyConnectFrom from '../components/KeyConnectForm'

export default {
  name: 'Home',
  components: {
    KeyConnectFrom
  }
}
</script>

<style lang="less">
  .home {
    background: #0f4fe3;
    height:100vh;
    width: 100vw;
    display:flex;
    justify-content:center;
    align-items:center;
  }
</style>
