<template>
<div class='nav-bar'>
    <a class='logo'><img src='src/assets/tinywhalelogo.png' alt='Template Logo' height='80px'></a>
    <h1 class='company-name' alt='company-name'>Template Replace</h1>
    <ul class='nav'>
        <router-link class='nav-link' :to="{ name: 'HomePage' }">Home</router-link>
        <router-link class='nav-link' to='Contact'>Contact</router-link>
        <router-link class='nav-link' to='About'>About</router-link>
        <!-- <li class='links'><a href='null'>Home</a></li>
        <li class='links'><a href='null'>Whales</a></li>
        <li class='links'><a href='null'>Pictures</a></li>
        <li class='links'><a href='null'>Profiles</a></li>
        <li class='links'><a href='null'>Contact</a></li> -->
    </ul>
    <div class='search-bar'>
        <input class='input-bar' type='text' placeholder='Search Here'><button><img alt='search-icon' src='null'> Search</button>
    </div>
    <router-link class='signup' to='Signup'>Sign-Up / Login</router-link>
</div>
</template>

<script>
export default {
    name: 'Nav-Bar',
    props: {

    }
}
</script>

<style scoped>
.nav-bar {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    padding: 0% 10px;
    background: #bfbfbf;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

ul  .nav-link{
    list-style: none;
    display: inline;
    padding: 10px;
    margin: 15px;
    justify-content: space-around;
}

a {
    text-decoration: none;
    color: white;
}

a:hover {
    border-bottom: solid 1px;
}

div .search-bar {
    float: right;
    padding: 10px;
    border: 3px solid #000000;
}
</style>
