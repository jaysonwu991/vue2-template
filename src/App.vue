<template>
  <div class="App">
    <router-link to="/">
      Home
    </router-link> | <router-link to="/medium">
      Medium
    </router-link>
    <router-view />
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html,
body {
  overflow: hidden;
  width: 100%;
  height: 100%;
}

.app {
  width: 100%;
  height: 100%;
}
</style>
