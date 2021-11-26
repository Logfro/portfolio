<template>
    <div>
        <img src="../assets/logo/tgm.svg" alt="">
        <img src="../assets/logo/bk.svg" alt="">
        <img src="../assets/logo/prive.svg" alt="">
        <img src="../assets/logo/viena.svg" alt="">       
    </div>
</template>

<script>

export default ({
    name: 'CompanyBar'
})
</script>

<style scoped>
    div {
        display: flex;
        justify-content: space-around;
        flex-direction: row;
        background-color: #2C2D33;
        width: 45vw;
        padding: 1.5rem 2rem;
        border-radius: 18px;
    }
    div img     {
        background-color: transparent;
    }
</style>