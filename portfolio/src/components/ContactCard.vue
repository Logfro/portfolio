<template>
    <div class="contact-card">
        <div class="info-container">
            <h3>Get in touch</h3>\
            <img src="" alt="">
        </div>
        <div class="input-container">
            <input type="text" name="name" id="name">
            <input type="text" name="email" id="email">
            <input type="text" name="msg" id="msg">
            <button>Send message =></button>
        </div>
    </div>
</template> 

<script>


export default ({

})
</script>

<style scoped>
    .contact-card   {
        display: flex;
        flex-direction: row;
    }
    .input-container    {
        display: flex;
        flex-direction: column;
    }
</style>