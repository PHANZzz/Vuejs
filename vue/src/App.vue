<template>
  <p>Choose what part of this page you want to see:</p>
 <div> <router-link to="/">Home</router-link>
  <br>
  <router-link to="/about">About</router-link><br></div>
  <div id="panel">
    <router-view></router-view>
  </div>
</template>
<style scoped>
#panel{
  width: 100%;
  height: 100%;
  background-color: blue;
}
</style>
