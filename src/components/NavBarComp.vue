<script setup>

</script>

<template>
<header>
    <div class="logo">
        <img src="../assets/img/Logo.svg" alt="Logo">
    </div>


    <div class="navbar">
<div class="nav-menu">
        <ul>
            <li><a href="#">Produtos</a><img src="../assets/img/Vector.svg" alt=""></li>
            <li><a href="#">Soluções</a><img src="../assets/img/Vector.svg" alt=""></li>
            <li><a href="#">Recursos</a><img src="../assets/img/Vector.svg" alt=""></li>
            <li><a href="#">Preços</a><img src="../assets/img/Vector.svg" alt=""></li>
        </ul>
    </div>

    <div class="button">
        <button class="login"><a href="#">Entrar</a></button>
        <button class="whitespacefree"><a href="#">Experimente o Whitespace</a><img src="../assets/img/Icon.svg" alt=""></button>
    </div>
    </div>

    
</header>
</template>

<style scoped>
header{
  width: 100%;
  height: 92px;  
  background-color: var(--background-color);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0px 200px
}

.navbar{
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.nav-menu {
    ul{
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 32px;
        
        li{
            width: 116px;
            list-style: none;
            display: flex;
            align-items: center;
            justify-content: space-around;
            a{
            color: var(--white);
            text-decoration: none;
            font-family: "DM Sans", sans-serif;
            font-size: 18px;
            }
        }
    }
}

.button{
    display: flex;
    align-items: center;
    justify-content: space-between;
    .login{
        width: 126px;
        height: 60px;
        border-radius: 8px;
        border: none;
        background-color: var(--first-color);
        margin-right: 24px;
        margin-left: 60px;
                a{
            text-decoration: none;
            color: var(--background-color);
            font-size: 18px;
            
        }
    }

    .whitespacefree{
        width: 267px;
        height: 60px;
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
