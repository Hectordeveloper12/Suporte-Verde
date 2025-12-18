<script setup>

</script>

<template>
<section class="project-section">

    <div class="left">
        <h1>100% your data</h1>
        <img src="../assets/img/Element6.svg" alt="" class="elemento">
        <p>The app is open source and your notes are saved to an open format, so you'll always have access to them. Uses End-To-End Encryption (E2EE) to secure your notes and ensure no-one but yourself can access them.</p>
        <button>
            <a href="#">Read more</a><img src="../assets/img/Icon.svg" alt="">
        </button>
    </div>

    <div class="right">
        <img src="../assets/img/Data.svg" alt="">
    </div>
</section>
</template>

<style scoped>
.project-section{
    width: 100%;
    height: 70vh;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    padding: 0px 220px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;

    .fundo{
        position: absolute;
        left: 0;
    }
}

.left{
    width: 672px;
    position: relative;
    h1{
        font-family: "Inter", sans-serif;
        font-size: 64px;
        margin-bottom: 24px;
        color: var(--black);
        z-index: 10;
        position: relative;

    }

    .elemento{
        position: absolute;
        top: 55px;
        left: 180px;
        z-index: 1;
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

</style>
