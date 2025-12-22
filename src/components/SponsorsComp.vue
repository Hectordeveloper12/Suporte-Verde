<script setup>

</script>

<template>
<section class="sponsors-section">

    <div class="content">
        <h1>Our sponsors</h1>
        <img src="../assets/img/Element6.svg" alt="" class="elemento">
    </div>

    <div class="logos">
        <img src="../assets/img/Apple.svg" alt="">
        <img src="../assets/img/Microsoft.svg" alt="">
        <img src="../assets/img/Slack.svg" alt="">
        <img src="../assets/img/Google.svg" alt="">
    </div>
</section>
</template>

<style scoped>
.sponsors-section{
    width: 100%;
    height: 40vh;
    padding: 0px 220px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;

    .fundo{
        position: absolute;
        left: 0;
    }
}

.content{
    width: 100%;
    position: relative;
    margin-bottom: 100px;
    h1{
        font-family: "Inter", sans-serif;
        font-size: 64px;
        margin-bottom: 24px;
        color: var(--black);
        z-index: 10;
        position: relative;
        text-align: center;
        width: 100;

    }

    .elemento{
        position: absolute;
        top: 40px;
        right: 350px;
        z-index: 1;
        width: 500px;
    }

    p{
        color: var(--black);
        font-family: "Inter", sans-serif;
        font-size: 18px;
        margin-bottom: 60px;
        font-weight: 200;
        position: relative;
    }

    button{
        width: 219px;
        height: 63px;
        border-radius: 8px;
        border: none;
        background-color: var(--second-color);
        display: flex;
        align-items: center;
        justify-content: space-evenly;
        
        a{
            text-decoration: none;
            color: var(--white);
            font-size: 18px;
        }
        
    }
}

.logos{
    display: flex;
    align-content: center;
    justify-content: space-between;
    width: 100%;
    padding: 0px 220px;
}

</style>
