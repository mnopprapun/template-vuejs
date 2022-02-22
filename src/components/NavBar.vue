<template>
<div class="nav">
    <!-- <div class="banner">
        <img src="#" alt="banner" />
    </div> -->
    <div class="nav-bar">
        <h1 class="logo"> Company Title</h1>
        <ul class="nav-links">
            <li>
                <a href="/">Home</a>
            </li>
            <li>
                <a href="/about">About</a>
            </li>
            <li>
                <a href="/contact">Contact</a>
            </li>
            <li>
                <a href="#">Link 4</a>
            </li>
        </ul>
        <div class="searchbar">
            <input placeholder="Search Here">
            <button class="search-btn">Search</button>
        </div>
        <button class="signin-up">Login/Signup</button>
    </div>
</div>
</template>

<script>

export default {
    name: 'Nav-Bar',
}
</script>

<style scoped>
.nav-bar{
    display: flex;
	justify-content: flex-end;
    align-items: center;
	border-bottom:1px solid;
	padding: 15px;
	background: #555;
}

.logo{
	margin-right: auto;
	cursor:pointer;
}

.nav-links {
	list-style: none;
	font-size: 18px;
}

.nav-links li {
	display: inline-block;
	padding: 0 15px;
}

.nav-links li a {
	color: #ffffff;
}

.nav-links li a:hover{
	color: #ffff;
}
</style>
