<script setup>

</script>

<template>
<section class="extension-section">

    <div class="left">
        <h1>Usar como extensão</h1>
        <img src="../assets/img/Element4.svg" alt="" class="elemento">
        <p>Use a extensão web clipper, disponível no Chrome e Firefox, para salvar páginas da web ou fazer capturas de tela como notas.</p>
        <button>
            <a href="#">Vamos lá</a>
        </button>
    </div>

    <div class="right">
        <img src="" alt="">
    </div>
</section>
</template>

<style scoped>
.extension-section{
    background-color: var(--background-color);
    width: 100%;
    height: 70vh;
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
        color: var(--white);
        z-index: 10;
        position: relative;

    }

    .elemento{
        position: absolute;
        top: 57px;
        right: 10px;
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
        width: 171px;
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
