<script setup>

</script>

<template>
<footer>
    <div class="content">
        <div class="divisor cntt1">
            <img src="../assets/img/Logo.svg" alt="">
            <p>O whitepace foi criado para as novas maneiras como vivemos e trabalhamos. Criamos um melhor espaço de trabalho em todo o mundo</p>
        </div>

        <div class="divisor">
            <h2>Produto</h2>
            <p>Visão geral</p>
            <p>Preços</p>
            <p>Histórias de clientes</p>
        </div>

        <div class="divisor">
            <h2>Recursos</h2>
            <p>Blog</p>
            <p>Guias e tutoriais</p>
            <p>Central de ajuda</p>
        </div>

        <div class="divisor">
            <h2>Empresa</h2>
            <p>Sobre nós</p>
            <p>Carreiras</p>
            <p>Kit de mídia</p>
        </div>

        <div class="divisor">
            <h1>Experimente hoje mesmo</h1>
            <p>Comece de graça. Adicione o seu <br> toda a equipe conforme suas necessidades crescem.</p>
            <button>Comece hoje</button>
        </div>
    </div>


    <div class="infos">
        <div class="left">
            <p>Português</p>
            <p>Termos e privacidade</p>
            <p>Segurança</p>
            <p>Status</p>
            <p>©2021 Whitepace LLC.</p>
        </div>
        
        <div class="right">
            <img src="../assets/img/facebook.svg" alt="">
            <img src="../assets/img/Twitter.svg" alt="">
            <img src="../assets/img/Linkedin.svg" alt="">
        </div>
    </div>
</footer>
</template>

<style scoped>
    footer{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        padding: 0px 220px;
        background-color: var(--background-color);
        color: var(--white);
        font-family: "Inter", sans-serif;
    }

    .content{
        display: flex;
        align-items: center;
        width: 1480px;
        justify-content: space-between;
        border-bottom: 1px solid var(--room-color);

        .divisor{
            height: 182px;
            display: flex;
            align-items: start;
            justify-content: start;
            flex-direction: column;
            h2{
                font-size: 18px;
                margin-bottom: 10px;
            }
            p{
                margin-bottom: 15px;
                font-size: 16px;
                font-weight: 200;
            }

            h1{
                font-size: 28px;
                margin-bottom: 10px;
            }

            button{
                width: 186px;
                height: 60px;
                background-color: var(--second-color);
                border: none;
                border-radius: 10px;
                font-size: 16px;
                color: var(--white);
            }
        }

        .cntt1{
            width: 205.25px;
        }
    }

.infos{
    width: 1480px;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .left{
        display: flex;
        align-items: start;
        justify-content: center;
        padding: 20px 0px;

        p{
            margin-right: 30px;
        }
    }

    .right{
        display: flex;
        align-items: start;
        justify-content: center;
        padding: 20px 0px;

        img{
            margin-left: 25px;
        }
    }
}
</style>