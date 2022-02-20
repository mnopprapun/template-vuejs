<template>
<section>
    <div class="circle"></div>
    <header>
        <NavBar />
    </header>
    <router-view />
</section>
</template>

<script>
import NavBar from './components/NavBar.vue'
// import Button from './components/ButtonLinks.vue'

export default {
    name: 'App',
    components: {
        NavBar,
        // Button
    }
}
</script>

<style>
* {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    box-sizing: border-box;
    padding: 0px;
    margin: 0px;
}

section {
    display: flex;
    position: relative;
    width: 100vw;
    min-height: 100vh;
    padding: 100px;
    margin: auto;
    justify-content: space-between;
    align-items: center;
    background-image: url("/Users/mathawudnopprapun/Development/vue/template/src/assets/pexels-tyler-lastovich-997443.jpg");
    background-size: 100% 100%;
    background-repeat: repeat;
}

</style>
