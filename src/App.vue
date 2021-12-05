<template>
  <div class="header">
    <div class="container">
    <div class="header_inner">
    <div class="nav">
      <router-link to="/">Главная</router-link>  
      <router-link to="/about">О нас | Запись </router-link> 
      <router-link to="/services">Услуги</router-link>
      <router-link to="/comands">Наша команда</router-link> 
    </div>
    </div>  
    </div>
    <router-view/>

<footer class="footer">
    <div class="container">
        <div class="footer__inner">
            <div class="footer__block">
                <h4 class="footer__title">Адрес:</h4>
                <address class="footer__address">
                    <div>ул. Островского 28а</div>
                    <div>ул. Щорса, 8Б, Белгород (этаж 2)</div>
                </address>
            </div>

            <div class="footer__block">
                <div class="footer__title">Связь с нами:</div>
                 <div class="footer__text">
                        <p>Vk || Instagram || Facebook</p>
                    </div>
            </div>

            <div class="footer__block">
                <div class="footer__title">Режим работы:</div>
                <div class="footer__text">
                    <p>Пн-Вс | 9:00 - 20:00</p>
                </div>
            </div>
        </div><!-- /.footer__inner -->
    </div><!-- /.container -->
    <div class="copyright">
        <div class="container">
            <div class="copyright__text">
                <div>© 2021 blackberry salon</div>
                <div>Made <span>by Semernina Ann</span></div>
            </div>
        </div>
    </div>
</footer>
  </div>     
</template>


<script>
import VBtn from './components/v-btn.vue'
import vMainWrapper from './components/v-main-wrapper.vue'

export default {
  name: 'app', 
  components: {
    vMainWrapper,
    VBtn
  }, 
  data(){
    return{
      message: 'Hello Vue!'
    }
  }
}
</script>

<style scoped>

/* Container
===================*/
.container {
    width: 110%;
    max-width: 1500px;
    margin: 0 auto;
    padding: 17px 5px;
}

/* Header
===================*/

.header {
    width: 100%;
    height: 100px;

    position: absolute;
    top: 0;
    left: 0;
    z-index: 1000;
}

.header__inner {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 35px 0;

    border-bottom: 1px solid #454655;
}


/* Nav
===================*/

.nav {
    display: flex;
    font-size: 15px;
    font-weight: 70;
    text-transform: uppercase;
}

.nav a {
    margin-left: 50px;
    color: rgb(22, 14, 22);
    text-decoration: none;
    opacity: .75;
    
    transition: opacity .1s linear;
}

.nav a.first-child {
    margin-left: 0;
}

.nav a.hover {
    opacity: 1;
}


/* Footer
===================*/

.footer {
    background-color: #501b44;
}

.footer__inner {
    display: flex;
    flex-wrap: wrap;
    padding: 30px 0;
    align-content: space-around;
    justify-content: space-between;
    align-items: baseline;
}

.footer__block {
    width: 30.33333%;
    padding: 0 10px;

    text-align: center;
}

.footer__title {
    margin-bottom: 10px;
    font-size: 14px;
    font-weight: 700;
    color: #fff;
    text-transform: uppercase;
}

.footer__address {
    font-size: 14px;
    line-height: 1.5;
    font-style: normal;
    color: rgba(255, 255, 255, .5);
}

.footer__text {
    font-size: 14px;
    line-height: 1.5;
    color: rgba(255, 255, 255, .5);
}

/* Copyright
===================*/

.copyright {
    padding: 20px 0;

    background-color: #c28bb6;
}

.copyright__text {
    text-align: center;
    font-size: 14px;
    line-height: 1.5;
    color: #808080;
}

.copyright__text span {
    color: #fff;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

</style>

