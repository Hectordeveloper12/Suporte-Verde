<script setup>

</script>

<template>
<section class="home-section">
    <div class="left">
        <h1>Get More Done with whitepace</h1>
        <p>Project management software that enables your teams to collaborate, plan, analyze and manage everyday tasks</p>
        <button>
            <a href="#">Try Whitespace free</a><img src="../assets/img/Icon.svg" alt="">
        </button>
    </div>

    <div class="right">
        <img src="" alt="">
    </div>
</section>
</template>

<style scoped>
.home-section{
    background: url("../assets/img/Hero-section.svg");
    width: 100%;
    height: 91.3vh;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    padding: 220px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

.left{
    width: 656px;
    h1{
        font-family: "Inter", sans-serif;
        font-size: 64px;
        margin-bottom: 24px;
        color: var(--white);
    }

    p{
        color: var(--white);
        font-family: "Inter", sans-serif;
        font-size: 18px;
        margin-bottom: 60px;
        font-weight: 200;
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

.right{
    background-color: var(--third-color);
    width: 824px;
    height: 549px;
}
</style>
