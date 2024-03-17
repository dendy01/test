<template>
  <div class="nav-menu">
    <div class="first"><a href="#">ГЛАВНАЯ</a></div>
    <div class="point"></div>
    <div><a href="#">НОВОСТИ</a></div>
    <div class="point"></div>
    <div><a href="#">СРЕДНЯЯ СТАВКА ПО ИПОТЕКЕ В РОССИИ ПРЕВЫСИЛА 8%</a></div>
  </div>
</template>

<style scoped>
  .nav-menu {
    margin-top: 30px;
    display: flex;

    .first {
      margin-left: 0px;
    }

    div {
      margin-left: 15px;
    }

    div>a {
      text-decoration: none;
      font-family: Onest;
      font-weight: 500px;
      color: #423F3F;
    }

    .point {
      width: 5px;
      height: 5px;
      margin-top: 7px;
      background: #423F3F;
      border-radius: 10px;
    }
  }
</style>