<template>
  <div>
    <div class="topnav">
      <div class="logo">0.2℃</div>
      <ul class="menu">
        <li>菜单1</li>
        <li>菜单2</li>
      </ul>
    </div>
    <div class="banner">
      <h1>0.2℃</h1>
      <h2>一个很厉害的UI 框架</h2>
      <p class="actions">
        <a href="">Github</a>
        <a href="">Start</a>
      </p>
    </div>
  </div>
</template>

<script>
  export default {
      
  }
</script>

<style lang="scss" scoped>
  .topnav {
  $bg:pink;
  background: $bg;
  display: flex;
  padding: 16px;
  > .logo {
    max-width: 6em;
    margin-right: auto;
  }
  > .menu {
    display: flex;
    white-space: nowrap;
    flex-wrap: nowrap;
    > li {
      margin: 0 1em;
    }
  }
}
</style>
