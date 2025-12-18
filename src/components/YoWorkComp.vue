<script setup>

</script>

<template>
<section class="yowork">
    <img src="../assets/img/BackYoWork.svg" alt="" class="back">
    <div class="content">
        <h1>Your work, everywhere you are</h1>
    <img src="../assets/img/Element7.svg" alt="">

        <p>Access your notes from your computer, phone or tablet by synchronising with various services, including whitepace, Dropbox and OneDrive. The app is available on Windows, macOS, Linux, Android and iOS. A terminal app is also available!</p>

        <button>
            <a href="#">Try Taskey</a>
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

        right: 200px;
        top: 60px;
        position: absolute;
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