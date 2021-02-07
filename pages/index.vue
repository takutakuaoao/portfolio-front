<template>
  <div class="container background">
    <div class="center">
      <div class="l_top">
        <div class="l_menu">
          <ul class="menu">
            <li class="menuList"><span>Profile</span></li>
            <li class="menuList"><span>Skill</span></li>
            <li class="menuList"><span>Contact</span></li>
          </ul>
        </div>
        <div class="l_title">
          <div class="l_subTitle">
            <div class="subTitle"><span>Takuya Aotsuka</span></div>
          </div>
          <div class="title">Portfolio</div>
        </div>
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
  background: #000000;
}

.center {
  display: flex;
  justify-content: center;
}

.l_menu {
  & .menuList {
    margin-bottom: 10px;
  }
}

.menu {
  &List {
    list-style: none;
    font-family: "Roboto";
    font-size: 12rem;
    color: #cacaca;
  }
}

.l_top {
  display: flex;
  justify-content: space-between;
  max-width: 1200px;
  width: 100%;
  padding-top: 7%;
}

.l_title {
  display: flex;
}

.title {
  font-family: "Roboto";
  display: block;
  font-size: 14rem;
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
