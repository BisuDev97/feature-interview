<template>
    <div class="section-footer">
        <div class="footer-wapper">
            <div class="footer-wappter-items first">
                <p>BASIC<br>
                (514) 904-6789<br>
                Quebec, 3100 Boulevard de la Côte-Vertu</p>
            </div>
            <div class="footer-wappter-items second">
                <p><a href="#">Activité 1</a></p>
                <p><a href="#">Activité 2</a></p>
                <p><a href="#">Activité 3</a></p>
            </div>
            <div class="footer-wappter-items third">
                <p><a href="#">Titre 1</a></p>
                <p><a href="#">Titre 2</a></p>
                <p><a href="#">Titre 3</a></p>
            </div>
            <div class="footer-wappter-items four">
                <p>Blog<br>Nous contacter</p>
            </div>
        </div>
        <div class="line-part"></div>
        <div class="social-link">
            <div class="social-link-item">
                <p>&copy; BASIC 2024</p>
            </div>
            <div class="social-icons">
                <a href="#"><img alt="Facebook" class="image-icon-social" src="@/assets/facebook.png"/></a>
                <a href="#"><img alt="Instagram" class="image-icon-social" src="@/assets/instagram.png"/></a>
                <a href="#"><img alt="Youtube" class="image-icon-social" src="@/assets/youtube.png"/></a>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .section-footer {
        background-color: #522e2c;
    }
    .footer-wapper {
        color: #fff;
        padding: 20px;
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        max-width: 1270px;
        margin: 0 auto;
        padding: 56px 15px 60px;
    }
    .footer-wapper .social-icons {
        display: flex;
        gap: 10px;
    }
    .social-icons a {
        text-decoration: none;
        color: #ff5733;
        font-size: 20px;
    }
    .footer-wappter-items p {
        margin-bottom: 0;
    }
    .social-link {
        display: flex;
        padding-top: 26px;
        max-width: 1270px;
        margin: 0 auto;
        padding: 26px 15px 15px;
        justify-content: space-between;
    }
    img.image-icon-social {
        width: 32px;
        height: 32px;
        object-fit: cover;
    }
    .social-icons {
        width: 110px;
        display: flex;
        justify-content: space-between;
    }   
    .first {
        font-size: 18px;
        font-family: 'Poppins',sans-serif;
        font-weight: 400;
        color: #FFFFFF;
    }
    .second a, .third a, .four p {
        font-size: 18px;
        font-family: 'Poppins',sans-serif;
        font-weight: 400;
        color: #FFFFFF99;
        text-decoration: none;
        position: relative;
    }
    .second a::after {
        content: '';
        position: absolute;
        width: 0;
        height: 2px;
        bottom: -2px;
        left: 0;
        background-color: #FFFFFF99;
        visibility: hidden;
        transition: all 0.3s ease-in-out;
    }
    .second a:hover::after {
        visibility: visible;
        width: 100%;
    }
    .third a::after {
        content: '';
        position: absolute;
        width: 0;
        height: 2px;
        bottom: -2px;
        left: 0;
        background-color: #FFFFFF99;
        visibility: hidden;
        transition: all 0.3s ease-in-out;
    }
    .third a:hover::after {
        visibility: visible;
        width: 100%;
    }
    .social-link-item p {
        font-size: 18px;
        font-family: 'Poppins', sans-serif;
        font-weight: 400;
        color: #FFFFFF;
    }
    .line-part {
        background-color: #FFFFFF4D;
        width: 1240px;
        height: 1px;
        margin: 0 auto;
    }
</style>