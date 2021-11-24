<template>
    <button>
        {{cap}}
    </button>
</template>

<script>

export default ({
    name: 'Button',
    props: {
        cap: String
    }

})
</script>

<style scoped>
    * {
        background-color: #FF3D4C;
    }
    button  {
        padding: 0.8rem 2rem;
        padding-top: 1rem;
        color: white;
        border-radius: 0.6rem;
        display: inline-block;
        border: none;
        font-size: 1.2rem;
        font-family: "Biotif-Medium";

    }
    button:hover    {
        cursor: pointer;
    }
</style>