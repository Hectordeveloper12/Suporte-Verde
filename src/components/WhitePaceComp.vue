<script setup>

</script>

<template>
<section class="yowork">
    <div class="content">
        <h1>Try Whitepace today</h1>

        <p>Get started for free. <br> Add your whole team as your needs grow.</p>

        <button>
            <a href="#">Try Taskey free</a>
        </button>

        <p>On a big team? Contact sales</p>
            <div class="logos">
        <img src="../assets/img/appleblack.svg" alt="">
        <img src="../assets/img/windows.svg" alt="">
        <img src="../assets/img/android.svg" alt="">
    </div>
    </div>


</section>
</template>

<style scoped>
.yowork{
    height: 60vh;
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

    .logos{
        width: 260px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    h1{
        font-size: 72px;
        margin-bottom: 24px;
        position: relative;
        z-index: 10;
    }

    p{
        width: 1064px;
        text-align: center;
        margin-bottom: 40px;
        font-size: 24px;
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
        margin-bottom: 40px;

        
        a{
            text-decoration: none;
            color: var(--white);
            font-size: 18px;
        }
    
    }
}
</style>