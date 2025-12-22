<script setup>

</script>

<template>
<section class="plan-section">
    <div class="content">
        <h1>Escolha seu plano</h1>
        <img src="../assets/img/Element6.svg" alt="">
        <p>Quer você queira se organizar, manter sua vida pessoal no caminho certo ou aumentar a produtividade no local de trabalho, o Evernote tem o plano certo para você.</p>
    </div>

    <div class="cards">
    <div class="side">
        <h3>Grátis</h3>
        <h2>$0</h2>
        <h4>Capture ideias e encontre-as rapidamente</h4>

        <div class="info">
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""> <p>Sincronize dispositivos ilimitados</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Uploads mensais de 10 GB</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Tamanho máximo da nota de 200 MB</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Personalize o painel inicial e acesse widgets extras</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Conecte a conta principal do Google Agenda</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Adicione datas de vencimento, lembretes e notificações às suas tarefas</p></div>
        </div>


        <button>
<a href="#">Comece agora mesmo</a>
        </button>
    </div>

    <div class="mid">
               <h3>Personal</h3>
        <h2>$11.99</h2>
        <h4>Keep home and family on track</h4>

        <div class="info">
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Sincronize dispositivos ilimitados</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Uploads mensais de 10 GB</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Tamanho máximo da nota de 200 MB</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Personalize o painel inicial e acesse widgets extras</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Conecte a conta principal do Google Agenda</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Adicione datas de vencimento, lembretes e notificações às suas tarefas</p></div>
        </div>


        <button>
<a href="#">Comece agora mesmo</a>
        </button>
    </div>

    <div class="side">
        <h3>Free</h3>
        <h2>$0</h2>
        <h4>Capture ideas and find them quickly</h4>

        <div class="info">
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""> <p>Sincronize dispositivos ilimitados</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Uploads mensais de 10 GB</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Tamanho máximo da nota de 200 MB</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Personalize o painel inicial e acesse widgets extras</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Conecte a conta principal do Google Agenda</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Adicione datas de vencimento, lembretes e notificações às suas tarefas</p></div>
        </div>


        <button>
<a href="#">Comece agora mesmo</a>
        </button>
    </div>

    </div>
</section>
</template>

<style scoped>
.plan-section{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    width: 100%;
    padding: 0px 220px;
    height: 120vh;
    position: relative;
}

.content{
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    font-family: "Inter", sans-serif;

    h1{
    position: relative;    
    font-size: 72px;
    font-weight: bold;
    z-index: 100;
    margin-bottom: 24px;
    }

    p{
        width: 979px;
        text-align: center;
        font-size: 18px;
        margin-bottom: 60px;
    }


    img{
        position: absolute;
        top: 60px;
        right: 160px;
        width: 250px;
    }
}

.cards{
    width: 1481px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 761px;
    font-family: "Inter", sans-serif;


    .side{
        width: 472.33px;
        height: 634px;
        border: 1px solid var(--first-color);
        border-radius: 10px;
        padding: 40px 44px;
        
        h3{
            font-size: 24px;
            font-weight: 500;
            margin-bottom: 30px;
        }
        h2{
            font-size: 36px;
            margin-bottom: 25px;
        }

        h4{
            margin-bottom: 30px;
        }

        .info{
            display: flex;
            align-items: start;
            justify-content: center;
            flex-direction: column;
            .englobar{
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: row;
                margin-bottom: 20px;
                p{
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    margin-left: 10px;
                    
                }
            }


        }

        button{
            width: 190px;
            height: 51px;
            border-radius: 8px;
            border: 1px solid var(--first-color);
            background: transparent;

            a{
                text-decoration: none;
                color: var(--black);
                font-size: 16px;
            }
        }
    }

    .mid{
        width: 472.34px;
        height: 100%;
        padding: 80px 44px;
        background-color: var(--background-color);
        border-radius: 10px;
        color: var(--white);

         h3{
            font-size: 24px;
            font-weight: 500;
            margin-bottom: 30px;
        }
        h2{
            font-size: 36px;
            margin-bottom: 25px;
            color: var(--first-color);
        }

        h4{
            margin-bottom: 30px;
        }

        .info{
            display: flex;
            align-items: start;
            justify-content: center;
            flex-direction: column;
            .englobar{
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: row;
                margin-bottom: 20px;
                p{
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    margin-left: 10px;
                    
                }
            }


        }

        button{
            width: 190px;
            height: 51px;
            border-radius: 8px;
            background: var(--second-color);
            border: none;

            a{
                text-decoration: none;
                color: var(--white);
                font-size: 16px;
            }
        }
    }
}
</style>
