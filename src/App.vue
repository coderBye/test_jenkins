<template>
  <div class="app">
    <h2>coderbye's app</h2>
    <router-link to="/">home</router-link>
    <router-link to="/about">about</router-link>
    <router-view></router-view>
  </div>
</template>

<style>
.app {
  color: red;
}
</style>
