<script setup>

</script>

<template>
<section class="project-section">

    <img src="../assets/img/BACKGROUND.svg" alt="logo" class="fundo">

    <div class="left">
        <h1>Project <br> Management</h1>
        <img src="../assets/img/Element2.svg" alt="" class="elemento">
        <p>Images, videos, PDFs and audio files are supported. Create math expressions and diagrams directly from the app. Take photos with the mobile app and save them to a note.</p>
        <button>
            <a href="#">Get Started</a><img src="../assets/img/Icon.svg" alt="">
        </button>
    </div>

    <div class="right">
        <img src="" alt="">
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
    justify-content: space-between;

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
        top: 95px;
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

.right{
    background-color: var(--third-color);
    width: 704px;
    height: 549px;
}
</style>
