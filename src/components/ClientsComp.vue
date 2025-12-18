<script setup>
    
</script>

<template>
<section class="clients-section">
    <div class="title">
        <h1>What Our Clients Says</h1>
        <img src="../assets/img/Element8.svg" alt="">
    </div>


    <div class="cards">
        <div class="card-white">

            <div class="top">
                <img src="../assets/img/Quote.svg" alt="">
                <p>Whitepate is designed as a collaboration tool <br> for businesses that is a full project management solution.</p>
            </div>
            
            <div class="perfil">
                <img src="../assets/img/Avater.svg" alt="">
                <div class="content-perfil">
                    <h1>Oberon Shaw, MCH</h1>
                    <p>Head of Talent Acquisition, North America</p>
                </div>
            </div>
            
        </div>

        <div class="card-blue">

            <div class="top">
                <img src="../assets/img/QuoteBlue.svg" alt="">
                <p>Whitepate is designed as a collaboration tool <br> for businesses that is a full project management solution.</p>
            </div>
            
            <div class="perfil">
                <img src="../assets/img/Avater2.svg" alt="">
                <div class="content-perfil">
                    <h1>Oberon Shaw, MCH</h1>
                    <p>Head of Talent Acquisition, North America</p>
                </div>
            </div>
        </div>

        <div class="card-blue">

            
            <div class="top">
                <img src="../assets/img/QuoteBlue.svg" alt="">
                <p>Whitepate is designed as a collaboration tool <br> for businesses that is a full project management solution.</p>
            </div>
            
            <div class="perfil">
                <img src="../assets/img/Avater3.svg" alt="">
                <div class="content-perfil">
                    <h1>Oberon Shaw, MCH</h1>
                    <p>Head of Talent Acquisition, North America</p>
                </div>
            </div>
        </div>
    </div>
</section>
</template>

<style scoped>
.clients-section{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    font-family: "Inter", sans-serif;
    height: 80vh;


}

.title{
    position: relative;
    h1{
        font-size: 70px;
        margin-bottom: 60px;
        position: relative;
        z-index: 10;
    }

    img{
        position: absolute;
        top: 30px;
        right: -80px;
    }
}

.cards {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    width: 100%;
    padding: 0px 220px;
    
    .card-white{
        width: 471.67px;
        height: 498.46px;
        padding: 60px 40px;
        box-shadow: 15px 10px 50px rgba(0, 0, 0, 0.144);
        border-radius: 10px;

        .top{
            border-bottom: 1px solid black;
            width: 391.67px;
            height: 223.46px;
            display: flex;
            align-items: start;
            justify-content: start;
            flex-direction: column;
            line-height: 25px;

            img{
                margin-bottom: 32px;
            }
        }

        .perfil{
            margin-top: 60px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 100%;

            .content-perfil{
                display: flex;
                align-items: start;
                justify-content: center;
                flex-direction: column;
                width: 246px;
            }
            h1{
                font-size: 24px;
                margin-bottom: 15px;
            }

            p{
                font-size: 16px;
            }
        }
    }


    .card-blue{
        width: 471.67px;
        height: 498.46px;
        padding: 60px 40px;
        box-shadow: 15px 10px 50px rgba(0, 0, 0, 0.144);
        border-radius: 10px;
        background-color: var(--second-color);
        color: var(--white);


        .top{
            border-bottom: 1px solid black;
            width: 391.67px;
            height: 223.46px;
            display: flex;
            align-items: start;
            justify-content: start;
            flex-direction: column;
            line-height: 25px;

            img{
                margin-bottom: 32px;
            }
        }

        .perfil{
            margin-top: 60px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 100%;

            .content-perfil{
                display: flex;
                align-items: start;
                justify-content: center;
                flex-direction: column;
                width: 246px;
            }
            h1{
                font-size: 24px;
                color: var(--background-color);
                margin-bottom: 15px;
            }

            p{
                font-size: 16px;
            }
        }
    }
}
</style>