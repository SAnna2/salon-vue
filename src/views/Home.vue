<template>
  <div class="home">
     <!-- <img alt="Vue logo" src="../assets/logo2.png">  -->
      <div class="intro">
      <div class="container">
          <div class="intro__inner">
             <h1 class="intro__title">СТУДИЯ НАРАЩИВАНИЯ РЕСНИЦ №1</h1>
            <h2 class="intro__subtitle">Индивидуальный подход к каждому клиенту, позволяет добиться желаемого результата!</h2>
              <vBtn/>
          </div>
      </div>
  </div>
  </div>
</template>

<style scoped>

/* Container
===================*/
.container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 15px;
}
/* Intro
===================*/

.intro {
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: 750px;
    padding-top: 100px;

    background: #0e0e16 url("../assets/f1.jpg") center no-repeat;
    background-size: cover;
}

.intro__inner {
    width: 100%;
    max-width: 970px;
    margin: 0 auto;

    text-align: center;
}

.intro__title {
    margin: 0 0 30px;

    font-family: 'Open Sans', sans-serif;
    font-size: 65px;
    line-height: 1.1;
    color: rgb(0, 0, 0);
    font-weight: 700;
    text-transform: uppercase;
}

.intro__subtitle {
    margin-bottom: 60px;

    font-size: 22px;
    color: rgb(0, 0, 0);
    line-height: 1.5;
    font-weight: 400;
}
</style>


