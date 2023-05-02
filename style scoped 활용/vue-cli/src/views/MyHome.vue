<template>
  <div>
    <h1>Home</h1>
    <br>
    <h2>첫 번째 박스</h2>
    <div class="global">
      <div class="box"></div>
    </div>
    <br>
    <h2>두 번째 박스</h2>
    <div class="global">
      <div class="box"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyHome'
}
</script>

<style>
  .global {
    display: flex;
    justify-content: center;
  }
  .box {
    border: solid;
    width: 100px;
    height: 100px;
  }
</style>