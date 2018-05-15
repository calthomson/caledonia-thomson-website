<template>
  <div>
    <nuxt/>
  </div>
</template>

<style>
html {
  font-family: monospace;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.button--blue {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #264653;
  color: #264653;
  text-decoration: none;
  padding: 10px 30px;
}

.button--blue:hover {
  color: #fff;
  background-color: #264653;
}

.button--orange {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #F09D51;
  color: #F09D51;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--orange:hover {
  color: #fff;
  background-color: #F09D51;
}
</style>
