<template>
<div class="wrapper">
    <div class="main-container">
    <div class="container-one">
        <div class="profile">
            <img src="../assets/ME.jpg" alt="">
            <h3>Onel Osbert M. Gundran</h3>
            <p>Web Delevoper</p>
        </div>
    <div class="social-links">
            <div class="link">
                <a href="">
                <img src="../assets/GitHub-Mark.png" alt="">
                <h2>Github</h2>
            </a>
            </div>
            <div class="link">
                <a href="">
                <img src="../assets/FACEBOOK.png" alt="">
                <h2>Facebook</h2>
            </a>
            </div>
            <div class="link">
                <a href="">
                <img src="../assets/X.png" alt="">
                <h2>X</h2>
            </a>
            </div>
            <div class="link">
                <a href="">
                <img src="../assets/INSTAGRAM.png" alt="">
                <h2>Instagram</h2>
            </a>
            </div>
            <div class="link">
                <a href="">
                <img src="../assets/TIKTOK.png" alt="">
                <h2>Tiktok</h2>
            </a>
            </div>
            <div class="link">
                <a href=""> 
                <img src="../assets/T.png" alt="">
                <h2>Telegram</h2>
            </a>
            </div>
            <div class="link">
                <a href="">
                <img src="../assets/P.png" alt="">
                <h2>Pinterest</h2>
            </a>
            </div>
            <div class="link">
                <a href="">
                <img src="../assets/LINKEDIN.png" alt="">
                <h2>Linkedin</h2>
            </a>
            </div>
    </div>
    </div>
    <div class="container-two">
        <div class="about-me">
            <h1>About Me</h1>
            <p>I have a degree in Information technology and a tech-savvy.
            I am a creative person and I have strong attention to detail.
            I am Passionate about photography and video editing
        </p>
        </div>
        <div class="technology-section">
            <h1>Technology Studies</h1>
            <div class="logos">
                <img src="../assets/download.png" alt="">
                <img src="../assets/C3.png" alt="">
                <img src="../assets/J2.png" alt="">
                <img src="../assets/REACT.png" alt="">
                <img src="../assets/VUE.png" alt="">
            </div>
        </div>
        <div class="button-container">
            <div class="projects-button">
            <a href="">My Projects</a>
        </div>
        <div class="projects-button">
            <a href="">My Resume</a>
        </div>
    </div>
</div>
</div>
</div>

</template>

<script>
export default {

}
</script>

<style scoped>
    img{
        height: 20px;
    }

    .wrapper {
        display: flex;
        justify-content: center;
    }
    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #cecece;
        border-radius: 25px;
        width: 60%;
        background-color: #a0daff;

    }

    .profile img{
        height: 5rem;
        border-radius: 50%;

    }

    .link a{
        text-decoration: none;
        color: #2c3e50;
        font-size: 10px;

    }

    .link img{
        height: 2rem;
    }
    .container-one{
        background-color: #1292EE;
        padding: 2.5%;
        width: 30%;
        border-radius: 25px;

    }
    .container-two{
        background-color: #cdc0fc;
        margin: 2.5%;
        width: 70%;
    }

    .about-me{
        text-align: left;
    }

    .logos img{
        height: 2.5rem;

    }

    .button-container{
        margin-top: 5%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .projects-button{
        background-color: #005ca4;
        border-radius: 15px;
        padding: 5px;
        margin: 5px;

    }
    
    .projects-button a{
        text-decoration: none;
        color: #fff;

    }


</style>