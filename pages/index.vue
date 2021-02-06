<template>
  <div class="container background">
    <div class="l_top">
      <div class="l_menu">
        <ul class="menu">
          <li class="menuList"><span>Profile</span></li>
          <li class="menuList"><span>Skill</span></li>
        </ul>
      </div>
      <div class="l_title">
        <div class="subTitle"><span>Takuya Aotsuka</span></div>
        <div class="title">Portfolio</div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style lang="scss">
.container {
  margin: 0 auto;
  min-height: 100vh;
}

.background {
  background: #222b30;
}

.l_top {
  display: flex;
  justify-content: space-between;
}

.l_title {
  display: flex;
}

.title {
  font-family: "Roboto";
  display: block;
  font-size: 120px;
  color: #cacaca;
  letter-spacing: 1px;
  writing-mode: vertical-lr;
}

.subTitle {
  font-family: "Roboto";
  writing-mode: vertical-lr;
  color: #cacaca;
  font-size: 40px;
  letter-spacing: 3px;
}

.letter {
  font-family: "Roboto";
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
