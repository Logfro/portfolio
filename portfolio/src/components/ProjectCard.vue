<template>
    <div>
        <sub>{{name}}</sub>
        <h4>{{desc}}</h4>
        <img src="" alt=""/>
    </div>
</template>

<script>

export default ({
    name: 'ProjectCard',
    props:  {
        name: String,
        desc: String,
        thumb: String
    }
})
</script>

<style scoped>
    div {
        background-color: #2C2D33;
        width: 30vw;
        height: 30vw;
        padding: 66px 44px;
        border-radius: 18px;
        display: flex;
        flex-direction: column;
    }
    sub {
    }
    h4  {
        margin-top: 18px;
    }
    img {
        background-color: #C4C4C4;
        height: 4rem;
        width: 4rem;
        position: relative;
        float: right;
        transform: translateX(44px);
        align-self: flex-end;
        bottom: -66px;
    }
</style>