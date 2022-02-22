<template>
<div>
    <div class='left-container'>
        <div class='left-text-box'>
            <h3>Lorem Ipsum</h3>
            <p>Lorem ipsum dolor sit amet. Eos unde voluptatem et doloremque ipsum ut ipsum esse. Cum molestiae voluptatem aut facilis illo qui nostrum quae eum doloribus galisum sit omnis ipsam ut dolores omnis ea suscipit inventore. Quo exercitationem molestiae qui assumenda esse et totam debitis aut optio necessitatibus.
            </p>
        </div>
        <div class='left-minor-container'>
            <CardBox/>
        </div>
    </div>
    <div class='right-container'>
        <FormBox/>
    </div>
</div>
</template>

<script>
import FormBox from '../components/FormBox.vue'
import CardBox from '../components/CardBox.vue'

export default {
    name: 'HomePage',
    components: {
        FormBox,
        CardBox,
    }
}
</script>

<style >
div .left-container {
    position: inherit;
    left: 0%;
    top: 85px;
    display: flex;
    flex-direction: column;
    border: solid rgb(0, 0, 0) 1px;
    width: 50vw;
    height: 100vh;
}

.left-text-box {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 100px;
}

.left-text-box h3 {
    font-size: 36px;
    margin-bottom: 20px;
}

.left-text-box p {
    margin-left: 25px;
}

.left-minor-container {
    display:flex;
    justify-content: center;
    align-items: center;
    position: relative;
    width: 25vw;
    height: 25vh;
    margin-top: 10%;
    margin-left: 25%;
    border: solid rgb(0, 0, 0) 1px;
}

div .right-container {
    position: absolute;
    left: 50%;
    top: 85px;
    display: flex;
    border: solid rgb(6, 6, 6) 1px;
}
</style>
