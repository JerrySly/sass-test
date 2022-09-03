<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div class="colors">
      <div class="color my"></div>
      <div class="color opposite"></div>
    </div>
    <div class="hover-block">
      <div class="item"></div>
    </div>
    <div class="hover-block">
      <div class="item item-blue"></div>
    </div>
    <div class="inner-block"></div>
    <h2 class="list-example">
      Scripts
    </h2>
    <div class="text-list">
      <div class="text--admin">Админ</div>
      <div class="text--employee">Работник</div>
      <div class="text--manager">Менеджер</div>
    </div>
    <div class="locale-imported"> <span class="imported">Lets import</span> </div>
  </div>
  <div style="display: flex; justify-content: space-between;">
  <div class="block"></div>
  <div class="my-block"></div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
}
</script>
<style scoped lang="scss">
.colors {
  display: flex;
  justify-content: space-around;
  .color {
    width: 200px;
    height: 220px;
    box-shadow: 1px 1px rgba(0, 0, 0, 0.247);
    border-radius: 8px;
  }
}
.hover-block {
  margin-top: 40px;
}
</style>
