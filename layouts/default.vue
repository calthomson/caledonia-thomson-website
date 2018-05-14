<template>
  <div>
    <nuxt/>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
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

.button--pink {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #FE5F55;
  color: #FE5F55;
  text-decoration: none;
  padding: 10px 30px;
}

.button--pink:hover {
  color: #fff;
  background-color: #FE5F55;
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
