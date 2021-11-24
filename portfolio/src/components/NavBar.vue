<template>
    <nav>
        <div ><a href=""><img class="logo" src="../assets/logo/personal_logo.svg" alt=""></a></div>
        <ul class="nav-links">
            <li> <a href="">About</a></li>
            <li><a href="">Contact</a></li>
            <li class="cta"><a href=""><Button cap="View work"></Button></a></li>
        </ul>
    </nav>
</template>

<script>

import Button from './Button.vue'

export default ({

    name: 'NavBar',
    components :    {
        Button
    }

})
</script>
<style scoped>
    nav {
        display: flex;
        align-items: center;
        justify-content: space-between;
        position: fixed;
        padding: 4vh 80px;
        width: 100vw;
        z-index: 1;
        border-bottom: 4px #FF3D4C solid;
    }

    ul {
    display: flex;
    gap: 1em;
    font-size: 18px;
    align-items: center;
    }
    ul li {
        padding: 5px 14px;

    }
    ul li a {
                font-family: "Biotif-Medium";
        padding-top: 0.2rem;
    }
    /* button  {
        background-color: red;
        height: 3.2rem;
    } */

    .cta    {
        padding: 0;
    }

    .logo   {
        height: 36px;
    }
</style>