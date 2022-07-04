<template>
   <div class="container">
    <div class="navbar">
        <div class="logo">
            <img class=logo_1 src="../assets/img/dog.gif" alt="logo" type="gif">
            <a href="#"><img class=logo_2 src="../assets/img/dazzv.png" alt="logo" type="png"></a>
        </div>
        <div class="nav">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Portfolio</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
        <div class="dark">
            <a href="#">Day/Night</a>
        </div>
    </div>
    <div class="home_body">
        <div class="links">
            <hr>
            <ul>
                <li><a href="https://github.com/Dazzv-King?tab=repositories"><img src="../assets/img/svg/github.svg" type="svg"></a></li>
                <li><a href="https://t.me/dazzvking"><img src="../assets/img/svg/tg.svg" type="svg"></a></li>
                <li><a href="https://career.habr.com/vlad-azizov"><img src="../assets/img/svg/habr.svg" type="svg"></a></li>
                <li><a href="https://wa.me/+79966249344"><img src="../assets/img/svg/ws.svg" type="svg"></a></li>
            </ul>
        </div>
        <div class="left_side">
            <h2>Hello<span>_</span></h2>
            <div class="im"><h1>I'm</h1><VueWriter :array="['Davlat', 'Coder', 'Designer']"/></div>
            <h4>Web developer who focused on creating functional and beautiful websites</h4>
            <!-- <button class="btn" type="button">Contact Me</button> -->
            <a class="button">
                <span>Contact Me</span>
                <span>Contact Me</span>
            </a>
        </div>
        <div class="right_side">
            <img src="../assets/img/me.png" alt="dazzv" type="png">
        </div>
    </div>
    </div> 
</template>

<script>
import VueWriter from 'vue-writer'

export default {
    name: "Home",
    components: { VueWriter }, //модуль объявил локально 

}
</script>

<style lang="scss" src="..\assets\style\styles.scss">

</style>