<script setup>

</script>

<template>
<section class="plan-section">
    <div class="content">
        <h1>Choose Your Plan</h1>
        <img src="../assets/img/Element6.svg" alt="">
        <p>Whether you want to get organized, keep your personal life on track, or boost workplace productivity, Evernote has the right plan for you.</p>
    </div>

    <div class="cards">
    <div class="side">
        <h3>Free</h3>
        <h2>$0</h2>
        <h4>Capture ideas and find them quickly</h4>

        <div class="info">
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""> <p>Sync unlimited devices</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>10 GB monthly uploads</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>200 MB max. note size</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Customize Home dashboard and access extra widgets</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Connect primary Google Calendar account</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Add due dates, reminders, and notifications to your tasks</p></div>
        </div>


        <button>
<a href="#">Get Started</a>
        </button>
    </div>

    <div class="mid">
               <h3>Personal</h3>
        <h2>$11.99</h2>
        <h4>Keep home and family on track</h4>

        <div class="info">
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Sync unlimited devices</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>10 GB monthly uploads</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>200 MB max. note size</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Customize Home dashboard and access extra widgets</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Connect primary Google Calendar account</p></div>
        <div class="englobar"><img src="../assets/img/Icon3.svg" alt=""><p>Add due dates, reminders, and notifications to your tasks</p></div>
        </div>


        <button>
<a href="#">Get Started</a>
        </button>
    </div>

    <div class="side">
        <h3>Free</h3>
        <h2>$0</h2>
        <h4>Capture ideas and find them quickly</h4>

        <div class="info">
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""> <p>Sync unlimited devices</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>10 GB monthly uploads</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>200 MB max. note size</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Customize Home dashboard and access extra widgets</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Connect primary Google Calendar account</p></div>
        <div class="englobar"><img src="../assets/img/Icon2.svg" alt=""><p>Add due dates, reminders, and notifications to your tasks</p></div>
        </div>


        <button>
<a href="#">Get Started</a>
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
    height: 100vh;
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
        left: 500px;
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
            width: 166px;
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
            width: 166px;
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
