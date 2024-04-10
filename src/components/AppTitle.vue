<script>
    export default {
        name: 'AppTitle'
    }
</script>

<template>
    <section class="jumbotron">
        <div class="container">     
        </div>
        <div class="title-area">
            <h1>La mia prima app con Vite!</h1>
        </div>
    </section>
</template>

<style>
    body {
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
    }

    .jumbotron {
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background-image: url('https://img.freepik.com/free-photo/abstract-colorful-splash-3d-background-generative-ai-background_60438-2509.jpg?w=1060&t=st=1712764871~exp=1712765471~hmac=b2c1d2f26ca476fed298ff7cc9c11b4495aac4f467bf023d80404ebeb9618655');
        background-size: cover;
        color: #ffffff;
    }

    .container {
        width: 100%;
        height: 200px;
        background-color: black;
        opacity: 0.6;
        position: relative;
    }

    .title-area {
        position: absolute;
        top: 45%;
        left: 25%;
    }

    h1 {
        color: #ffffff;
        font-size: 50px;
        font-weight: 700;
        text-align: center;
    }
</style>