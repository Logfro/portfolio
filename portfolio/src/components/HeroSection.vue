<template>
    <div class="hero">
        <h1>
            Goldmann,
            <br>
            <u>UX/UI-Designer</u>
            
        </h1>
        <p>My name is Farid Goldmann and I’m a passionate designer based in Vienna, Austria.
            <br>
            I bring a burning passion and profound empathy to the conversation.
        </p>
        <a href=""><Button cap="View my work"/></a>
        <ul class="social-icons">
            <li><a href=""><img src="../assets/social-icons/linked_in.svg" alt="LinkedIn Logo"></a></li>
            <li><a href=""><img src="../assets/social-icons/xing.svg" alt="Xing Logo"></a></li>
        </ul>

    </div>
</template>

<script>
import Button from './Button.vue'
export default ({

    name: 'HeroSection',
    components: {
        Button
    }
})
</script>

<style scoped>
    p   {
        font-family: "Biotif-Book";
        font-size: 1.6rem;
        margin-bottom: 24px;
        line-height: 1.5;
    }

    .hero   {
        height: 100vh;
        display: flex;
        align-items: flex-start;
        justify-content: center;
        flex-direction: column;
    }
    .social-icons   {
        position: absolute;
        bottom: 0;
        margin-bottom: 4vh;
    }
</style>
