<script setup>

</script>

<template>
<section class="app-section">

    <div class="left">
        <img src="../assets/img/Apps.svg" alt="">
    </div>

    <div class="right">
        <h1>Trabalhe com seus aplicativos favoritos usando whitepace
</h1>
        <p>A Whitepace se une ao seu software favorito. Integre-se com mais de 1000+ aplicativos com o Zapier para ter todas as ferramentas necessárias para o sucesso do seu projeto.
</p>
        <button>
            <a href="#">Saiba mais</a><img src="../assets/img/Icon.svg" alt="">
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
