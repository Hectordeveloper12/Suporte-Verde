<script setup>

</script>

<template>
<section class="app-section">

    <div class="left">
        <img src="../assets/img/Apps.svg" alt="">
    </div>

    <div class="right">
        <h1>Work with Your Favorite Apps Using whitepace</h1>
        <img src="../assets/img/Element3.svg" alt="" class="elemento">
        <p>Whitepace teams up with your favorite software. Integrate with over 1000+ apps with Zapier to have all the tools you need for your project success.
</p>
        <button>
            <a href="#">Read more</a><img src="../assets/img/Icon.svg" alt="">
        </button>
    </div>

</section>
</template>

<style scoped>
.app-section{
    width: 100%;
    height: 70vh;
    padding: 0px 220px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background: url('../assets/img/BackApps.svg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;


    .fundo{
        position: absolute;
        left: 0;
    }
}

.right{
    position: relative;
    width: 672px;
    h1{
        font-family: "Inter", sans-serif;
        font-size: 64px;
        margin-bottom: 24px;
        color: var(--white);
        z-index: 10;
        position: relative;

    }

    .elemento{
        position: absolute;
        top: 2080px;
        right: 490px;
        z-index: 1;
    }

    p{
        color: var(--white);
        font-family: "Inter", sans-serif;
        font-size: 18px;
        margin-bottom: 60px;
        font-weight: 200;
        position: relative;
    }

    button{
        width: 186px;
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
