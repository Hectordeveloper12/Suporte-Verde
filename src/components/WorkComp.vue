<script setup>

</script>

<template>
<section class="work-section">

    <div class="left">
        <img src="../assets/img/WorkBackground.svg" alt="">
    </div>

    <div class="right">
        <h1>Work together</h1>
        <img src="../assets/img/Element3.svg" alt="" class="elemento">
        <p>With whitepace, share your notes with your colleagues and collaborate on them. You can also publish a note to the internet and share the URL with others.
</p>
        <button>
            <a href="#">Try it now</a><img src="../assets/img/Icon.svg" alt="">
        </button>
    </div>

</section>
</template>

<style scoped>
.work-section{
    width: 100%;
    height: 70vh;
    padding: 0px 220px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    margin-bottom: 140px;

    .fundo{
        position: absolute;
        left: 0;
    }
}

.right{
    width: 672px;
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
        top: 2080px;
        right: 490px;
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
