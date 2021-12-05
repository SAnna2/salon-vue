<template>
<div class="container">
    <div class="features">
        <div class="features__item">
            <img class="team__photo" src="../assets/img/team/t_1.png" alt="">
            <h4 class="features__title">Наращивание ресниц</h4>
            <div class="features__text">Наши профессионалы выполнят все виды наращивания, используя только премиум материалы.</div>
        </div>

        <div class="features__item">
             <img class="team__photo" src="../assets/img/team/t_2.png" alt="">
            <h4 class="features__title">Броу бар</h4>
            <div class="features__text">Идеальные брови наш конек. Правильно подобранная форма и цвет бровей помогут сделать твое лицо более гармоничным.</div>
        </div>

        <div class="features__item">
            <img class="team__photo" src="../assets/img/team/t_3.png" alt="">
            <h4 class="features__title">Маникюр</h4>
            <div class="features__text">Наша концепция — красивые и ухоженные руки. Мы за безупречное качество маникюра и минимализм в дизайне.</div>
        </div>

        <div class="features__item">
            <img class="team__photo" src="../assets/img/team/t_4.png" alt="">
            <h4 class="features__title">Педикюр</h4>
            <div class="features__text">Наша концепция — красивые и ухоженные ножки. Мы за безупречное качество педикюра и минимализм в дизайне.</div>
        </div>

        <div class="features__item">
            <img class="team__photo" src="../assets/img/team/t_2.png" alt="">
            <h4 class="features__title">Укладки</h4>
            <div class="features__text">Готова изменить свой образ и улучшить настроение? Все виды окрашивания от балаяж до шатуш. Супермодные стрижки.</div>
        </div>

        <div class="features__item">
           <img class="team__photo" src="../assets/img/team/t_3.png" alt="">
            <h4 class="features__title">Визаж</h4>
            <div class="features__text">В команде работают лучшие визажисты Белгорода. Наша основная философия в макияже — естественность и натуральность.</div>
        </div>
    </div><!-- /.features -->
</div><!-- /.container -->
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

/* Features
===================*/
.features {
    display: flex;
    flex-wrap: wrap;
    margin: 0px 15px;
    align-content: flex-end;
    justify-content: space-around;
}

.features__item {
    width: 33.33333%;
    padding: 0 40px;
    margin: 25px 0;

    text-align: center;
}

.features__icon {
    margin-bottom: 25px;
}

.features__title {
    margin-bottom: 20px;

    font-size: 14px;
    color: #2d3033;
    font-weight: 700;
    text-transform: uppercase;
}

.features__text {
    font-size: 14px;
    line-height: 1.5;
    color: #6c7279;
}

.team__photo {
    display: block;
    max-width: 100%;
    height: auto;
    margin-bottom: 20px;
}

</style>