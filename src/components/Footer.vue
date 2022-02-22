<template>
<div class="footer">
    <!-- Footer main -->
    <div class="ft-main">
        <div class="ft-main-item">
            <h2 class="ft-title">About</h2>
            <ul>
                <li><a href="#">Services</a></li>
                <li><a href="#">Portfolio</a></li>
                <li><a href="#">Pricing</a></li>
                <li><a href="#">Customers</a></li>
                <li><a href="#">Careers</a></li>
            </ul>
        </div>
        <div class="ft-main-item">
            <h2 class="ft-title">Resources</h2>
            <ul>
                <li><a href="#">Docs</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">eBooks</a></li>
                <li><a href="#">Webinars</a></li>
            </ul>
        </div>
        <div class="ft-main-item">
            <h2 class="ft-title">Contact</h2>
            <ul>
                <li><a href="#">Help</a></li>
                <li><a href="#">Sales</a></li>
                <li><a href="#">Advertise</a></li>
            </ul>
        </div>
    </div>
    <!-- Footer social -->
    <section class="ft-social">
        <ul class="ft-social-list">
            <li><a href="#">Facebook Icon</a></li>
            <li><a href="#">Twitter Icon</a></li>
            <li><a href="#">Social Media Icon</a></li>
        </ul>
    </section>
    <!-- Footer legal -->
    <section class="ft-legal">
        <ul class="ft-legal-list">
            <li><a href="#">Terms &amp; Conditions</a></li>
            <li><a href="#">Privacy Policy</a></li>
            <li>&copy; 2022 Copyright Company Inc.</li>
        </ul>
    </section>
</div>
</template>

<script>
export default {
    name: 'v-Footer',
    props: {

    }
}
</script>

<style scoped>
.footer {
    justify-content: space-between;
    background-color: #555;
    color: #bbb;
    line-height: 1.5;
}

li {
    list-style: none;
}

.footer a {
    text-decoration: none;
    color: #eee;
}

a:hover {
    text-decoration: underline;
}

.ft-title {
    color: #fff;
    font-size: 24px;
    padding-bottom: 14px;
}

.ft-main {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.ft-main-item {
    padding: 12px;
    min-width: 200px;
}

.ft-social {
    padding: 0 15px 20px;
}

.ft-social-list {
    display: flex;
    justify-content: center;
    border-top: 1px #777 solid;
    padding-top: 15px;
}

.ft-social-list li {
    margin: 10px;
}

.ft-legal {
    padding: 0.9375rem 1.875rem;
    background-color: #333;
}

.ft-legal-list {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
}

.ft-legal-list li {
    margin: 0.125rem 0.625rem;
    white-space: nowrap;
}

.ft-legal-list li:nth-last-child(2) {
    flex: 1;
}
</style>
