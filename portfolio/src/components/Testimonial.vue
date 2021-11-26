<template>
    <div class="quote-wrapper">
            <blockquote class="quote-card">
                <p>
                    Farid Goldmann has a broad range of strengths. As a talented UX/UI-Designer 
                    he is always ready to help others. Furthermore, Farid Goldmann distinguishes 
                    himself by the fact that his commitment goes far beyond what is required.
                </p>
                <Button cap="More about me"/>
            </blockquote>
        <div class="person-info">                
            <img src="" alt="">
            <div class="person-name">

                <h4>Dr. Gottfried <br/>Koppensteiner</h4>
                <p>TGM, Head of Department<br>
                Information Technology</p>
            </div>

        </div>
    </div>
</template>

<script>
import Button from './Button'
export default ({
    name: 'Testimonial',
    components: {
        Button
    }
})
</script>

<style scoped>
    .quote-card {
        background-color: #2C2D33;
        padding: 30px 90px;
        width: 40%;
        border-radius: 18px;
        padding-bottom: 40px;
    }
    .quote-card blockquote   {
        background: transparent;
    }
    blockquote::before  {
        content: "\201c";
        font-size: 400px;
        color: #4B4C51;
        display: block;
        margin-bottom: -320px;
        margin-top: -200px;
        margin-left: -70px
    }
    .quote-card h1  {
        background: transparent;
    }
    .quote-wrapper  {
        display: flex;
        flex-direction: row;
        margin-top: 40px;
        justify-content: center;
    }
    blockquote p    {
        background: transparent;
        font-family: "Biotif-MediumItalic";
        font-weight: normal;
        font-size: 1.4rem;
        margin-bottom: 20px;
        color: #D3D3D3;
        line-height: 1.7;
    }
    img {
        background: grey;
        border-radius: 100%;
        width: 165px;
        height: 165px;
        margin-left: -50px;
        border: 3px solid #FF3D4C;
    }
    .person-info    {
        display: flex;
        flex-direction: row;
        padding-top: 20px;
        align-items: center; 
        height: 60%;
    }
    .person-name    {
        margin-left: 24px;
    }
    h4  {
        font-weight: normal;
        margin-bottom: 10px;
    }
    .person-name p   {
        color: #D3D3D3;
        font-family: "Biotif-Book";
    }
</style>