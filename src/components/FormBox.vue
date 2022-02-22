<template>
<div class='form-box'>
    <form class="card">
    <h2>Title</h2>
        <p>First Name</p>
        <input placeholder='First Name'>
        <p> Name </p>
        <input placeholder='Last Name'>
        <p> E-Mail </p>
        <input placeholder='E-Mail'>
        <button>Submit</button>
    </form>
</div>
</template>

<script>

</script>

<style scoped>

.form-box {
    position: absolute;
    width: auto;
    height: auto;
    padding: 40px;
    margin: 40px;
    border: solid white 1px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
}

.card{
    display: flex;
    flex-direction: column;
    align-items: left;
}


</style>
