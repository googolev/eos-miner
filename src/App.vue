<template>
  <div id="app">
    <HeaderBar />
    <router-view/>
  </div>
</template>

<script>
import HeaderBar from '../src/components/HeaderBar'

export default {
  name: 'app',
  components: {
    HeaderBar
  }
}
</script>

<style lang="less">
body {
  position: relative;
  margin: 0;
  overflow-x: hidden;
  padding-top: 60px;
}

.wrap-input {
  width: 100%;
  background-color: #fff;
  border-radius: 31px;
  margin-bottom: 16px;
  display: flex;
  input {
    height: 62px;
    padding: 0 35px 0 35px;
    font-family: 'Ubuntu', sans-serif;
    position: relative;
    display: block;
    width: 100%;
    background: #fff;
    border-radius: 31px;
    font-family: Ubuntu-Bold;
    font-size: 18px;
    color: #8f8fa1;
    line-height: 1.2;
    &:focus {
      outline: none;
    }
  }
}
</style>

