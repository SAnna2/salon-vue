<template>
<div class="team">
    <div class="container">
        <div class="team__inner">

            <div class="team__item">
                <img class="team__photo" src="../assets/img/team/t_6.png" alt="">
                <div class="team__name">Надтока Анастасия</div>
                <div class="team__prof">Топ-мастер</div>
                <div class="team__text">
                    <p>В индустрии красоты с 2019 года. В 2020 выйграла чемпионат по наращиванию ресниц.</p>
                    <p>Любит делать красоту на людях и вокруг себя. </p>
                </div>
            </div>

            <div class="team__item">
                <img class="team__photo" src="../assets/img/team/t_7.png" alt="">
                <div class="team__name">Карпова Наталья</div>
                <div class="team__prof">Мастер-универсал</div>
                <div class="team__text">
                    <p>В сфере красоты, а именно в наращивании ресниц 2 года.</p>
                    <p>Активно проходит обучение и повышает квалификацию в индустрии красоты.</p>
                </div>           
            </div>

            <div class="team__item">
                <img class="team__photo" src="../assets/img/team/t_8.png" alt="">
                <div class="team__name">Польская Алина</div>
                <div class="team__prof">Топ-мастер ногтевого сервиса</div>
                <div class="team__text">
                    <p>Мастер самоучка. В сфере более 5 лет.</p>
                    <p>Имеет большое количество отзывов от клиентов, любит нежность и аккуратность.</p>
                </div>              
            </div>

            <div class="team__item">
                <img class="team__photo" src="../assets/img/team/t_9.png" alt="">
                <div class="team__name">Федюшина Василиса</div>
                <div class="team__prof">Мастер ногтевого сервиса</div>
                <div class="team__text">
                    <p>В ногтевой сфере более 5 лет.</p>
                    <p>Умеет подобрать нужный дизайн и форму ногтей клиенту.</p>
                </div>           
            </div>

        </div><!-- /.team__inner -->
    </div><!-- /.container -->
</div><!-- /.team -->
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

/* Team
===================*/
.team {
    margin: 10px 10px;
      display: flex;
    flex-wrap: wrap;
    align-content: flex-end;
    justify-content: space-around;
}

.team__inner {
    display: flex;
    flex-wrap: nowrap;
    margin: 0 -15px;

}

.team__item {
    width: 25%;
    padding: 0 15px;
    margin-bottom: 30px;
}

.team__photo {
    display: block;
    max-width: 100%;
    height: auto;
    margin-bottom: 20px;
}

.team__name {
    margin-bottom: 8px;

    font-size: 22px;
    color: #2d3033;
}

.team__prof {
    margin-bottom: 15px;

    font-size: 13px;
    color: #501b44;
    text-transform: uppercase;
}

.team__text {
    margin-bottom: 20px;

    font-size: 14px;
    line-height: 1.5;
    color: #6c7279;
}
</style>