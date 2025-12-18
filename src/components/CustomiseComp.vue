<script setup>

</script>

<template>
<section class="customise-section">

    <div class="left">
        
    </div>

    <div class="right">
        <h1>Customise it to <br> your needs</h1>
        <img src="../assets/img/Element5.svg" alt="" class="elemento">
        <p>Customise the app with plugins, custom themes and multiple text editors (Rich <br> Text or Markdown). Or create your own scripts and plugins using the Extension <br> API.
</p>
        <button>
            <a href="#">Let’s Go</a><img src="../assets/img/Icon.svg" alt="">
        </button>
    </div>

</section>
</template>

<style scoped>
.customise-section{
    width: 100%;
    height: 80vh;
    padding: 0px 220px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;

    .fundo{
        position: absolute;
        left: 0;
    }
}

.right{
    width: 669px;
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
        right: 25px;
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
        justify-content: center;
        
        a{
            text-decoration: none;
            color: var(--white);
            font-size: 18px;
            margin-right: 10px;
        }
        
    }
}

.left{
    background-color: var(--third-color);
    width: 704px;
    height: 549px;
}
</style>
