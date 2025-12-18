<script setup>

</script>

<template>
<footer>
    <div class="content">
        <div class="divisor cntt1">
            <img src="../assets/img/Logo.svg" alt="">
            <p>whitepace was created for the new ways we live and work. We make a better workspace around the world</p>
        </div>

        <div class="divisor">
            <h2>Product</h2>
            <p>Overview</p>
            <p>Pricing</p>
            <p>Customer stories</p>
        </div>

        <div class="divisor">
            <h2>Resources</h2>
            <p>Blog</p>
            <p>Guides & tutorials</p>
            <p>Help center</p>
        </div>

        <div class="divisor">
            <h2>Company</h2>
            <p>About us</p>
            <p>Careers</p>
            <p>Media kit</p>
        </div>

        <div class="divisor">
            <h1>Try It Today</h1>
            <p>Get started for free. Add your <br> whole team as your needs grow.</p>
            <button>Start today</button>
        </div>
    </div>


    <div class="infos">
        <div class="left">
            <p>English</p>
            <p>Terms & privacy</p>
            <p>Security</p>
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