<template>
  <section class="container">
    <div>
      <img src='/portrait.jpg' class="portrait"/>
      <h1 class="title">
        Caledonia Thomson
      </h1>
      <h2 class="subtitle">
        Software Developer
      </h2>
      <div class="links">
        <a
          href="https://github.com/calthomson"
          target="_blank"
          class="button--blue">GitHub</a>
        <a
          href="http://vegemitesoup.com/"
          target="_blank"
          class="button--orange">Blog</a>
      </div>
    </div>
  </section>
</template>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin-left: 20px;
  margin-right: 20px;
}

.title {
  animation: fadeIn 1s ease-in both;
  font-family: monospace;
  display: block;
  font-weight: 300;
  font-size: 5em;
  color: #313638;
  letter-spacing: 1px;
}

.subtitle {
  animation: fadeIn 1s ease-in both;
  animation-delay: .5s;
  font-weight: 300;
  font-size: 3em;
  color: #FE5F55;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  animation: fadeIn 2s ease-in both;
  animation-delay: .5s;
  padding-top: 15px;
}

.portrait {
  animation: fadeInDown 1s ease-in both;
  border-radius: 50%;
  height: auto;
  max-width: 40%;
}

@media only screen and (max-width: 450px) {
  .title {
    font-size: 4em;
  }

  .subtitle {
    font-size: 1.8em;
  }
}

@keyframes fadeInDown {
   0% {
      opacity: 0;
      transform: translateY(-20px);
   }
   100% {
      opacity: 1;
      transform: translateY(0);
   }
}

@keyframes fadeIn {
   0% {
      opacity: 0;
   }
   100% {
      opacity: 1;
   }
}

</style>
