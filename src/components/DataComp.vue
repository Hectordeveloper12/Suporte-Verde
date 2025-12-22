<script setup>

</script>

<template>
<section class="project-section">

    <div class="left">
        <h1>100% seus dados</h1>
        <img src="../assets/img/Element6.svg" alt="" class="elemento">
        <p>TO aplicativo é de código aberto e suas anotações são salvas em formato aberto, para que você sempre tenha acesso a elas. Usa criptografia ponta a ponta (E2EE) para proteger suas anotações e garantir que não há nenhum acesso.</p>
        <button>
            <a href="#">Saiba mais</a><img src="../assets/img/Icon.svg" alt="">
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
        right: 120px;
        z-index: 1;
        width: 230px;
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
        width: 160px;
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
