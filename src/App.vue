<template>
<header>
    <nav class="nav">
        <a href="#" class="logo">Recrui<span>Nex</span></a>
        <div class="nav__content">
            <ul class="nav__content">
                <li><a href="#">About us</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Market expertise</a></li>
                <li><a href="#">Clients</a></li>
                <li><a href="#">Contacts</a></li>
            </ul>
        </div>
    </nav>
</header>

<main class="main">
    
    <MainScreen />
    <AboutUs />
    <Services />

</main>
</template>

<script>
import MainScreen from './components/MainScreen.vue';
import AboutUs from './components/AboutUs.vue';
import Services from './components/Services.vue';

export default {
    components: {
        MainScreen,
        AboutUs,
        Services,
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body {
    background: #F5F8FF;
}
a {
    text-decoration: none;
}
li {
    list-style: none;
}
.main {
    display: flex;
    flex-direction: column;
    gap: 140px;
    padding: 90px 75px 160px;
}

.nav {
    height: 82px;
    border-radius: 0px 0px 20px 20px;
    padding: 0 78px;
    background: #FFF;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    color: #363636;
    text-align: center;
    font-family: Poppins;
    font-size: 30px;
    font-style: normal;
    font-weight: 600;
    line-height: 60px;
}
.logo span {
    color: #2F0899;
    font-family: Poppins;
    font-size: 30px;
    font-style: normal;
    font-weight: 600;
    line-height: 60px;
}

.nav__content {
    display: inline-flex;
    gap: 50px;
}
.nav__content a {
    color: #363636;
    text-align: center;
    font-family: Poppins;
    font-size: 24px;
    font-style: normal;
    font-weight: 300;
    line-height: 60px;
}
</style>
