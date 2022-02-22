<template>
<section>
    <header>
        <NavBar />
    </header>
    <body>
        <router-view />
    </body>
<Footer />
</section>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'

export default {
    name: 'App',
    components: {
        NavBar,
        Footer,
    }
}
</script>

<style>
* {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    box-sizing: border-box;
    padding: 0px;
    margin: 0px;
    color: rgb(0, 0, 0);
}

section {
     background: rgb(60, 60, 60);
}
</style>
