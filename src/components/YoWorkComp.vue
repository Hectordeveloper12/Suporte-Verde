<script setup>

</script>

<template>
<section class="yowork">
    <img src="../assets/img/BackYoWork.svg" alt="" class="back">
    <div class="content">
        <h1>Seu trabalho, onde quer que você esteja</h1>
    <img src="../assets/img/Element7.svg" alt="">

        <p>Acesse suas anotações pelo computador, telefone ou tablet sincronizando com vários serviços, incluindo whitepace, Dropbox e OneDrive. O aplicativo está disponível para Windows, macOS, Linux, Android e iOS. Um aplicativo de terminal também está disponível!</p>

        <button>
            <a href="#">Experimente Taskey</a>
        </button>
    </div>
</section>
</template>

<style scoped>
.yowork{
    height: 52vh;
    width: 100%;
    background-color: var(--background-color);
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;

    .back{
        position: absolute;
        top: -203px;
        left: 0;
    }
}

.content{
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0px 220px;
    font-family: "Inter", sans-serif;
    color: var(--white);

    h1{
        font-size: 72px;
        margin-bottom: 24px;
        position: relative;
        z-index: 10;
    }

    img{

        right: 185px;
        top: 63px;
        position: absolute;
        width: 240px;
    }
    p{
        width: 1064px;
        text-align: center;
        margin-bottom: 60px;
    }

        button{
        width: 195px;
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