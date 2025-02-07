<template>
    <div class="wrapper-section">
        <section class="experience-section">
            <div class="content">
                <h1>DES EXPÉRIENCES INOUBLIABLES <span class="special-text">LOREM IPSUM TRUC</span></h1>
                <div class="wrapper-description">
                    <div class="line-x"></div>
                    <div class="description">
                        <h2>À Propos De BASIC</h2>
                        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</p>
                    </div>
                </div>
            </div>
            <div class="image-container">
                <img alt="Ice-cream Image" class="image-ice-cream" src="@/assets/ice-cream.png"/>
            </div>
        </section>
        <div class="features">
            <div class="feature">
                <img alt="Icon Image" class="image-icon-image" src="@/assets/icon container.png"/>
                <h3>Authenticité</h3>
                <p>Sous-titre</p>
            </div>
            <div class="feature">
                <img alt="Icon Image" class="image-icon-image" src="@/assets/container.png"/>
                <h3>Respect</h3>
                <p>Sous-titre</p>
            </div>
            <div class="feature">
                <img alt="Icon Image" class="image-icon-image" src="@/assets/containerworld.png"/>
                <h3>Diversité</h3>
                <p>Sous-titre</p>
            </div>
            <div class="feature">
                <img alt="Icon Image" class="image-icon-image" src="@/assets/containercycle.png"/>
                <h3>Personnalisation</h3>
                <p>Sous-titre</p>
            </div>
            <div class="feature">
                <img alt="Icon Image" class="image-icon-image" src="@/assets/iconsmile.png"/>
                <h3>Confort</h3>
                <p>Sous-titre</p>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .wrapper-section {
        max-width: 1270px;
        margin: 0 auto;
        padding: 0 15px;
    }
    .content .special-text {
        font-family: 'Poppins',sans-serif;
        font-size: 48px;
        font-weight: 600;
        color: #F2542D99;
    }
    .content h1 {
        font-family: 'Poppins',sans-serif;
        font-size: 48px;
        font-weight: 600;
        color: #F2542D;
        padding-top: 50px;
    }
    .experience-section {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 80px 0 0 0;
    }

    .wrapper-description {
        display: flex;
        padding-top: 50px;
    }

    .line-x {
        width: 81px;
        height: 2px;
        background-color: #bbbbbb;
        margin-top: 15px;
    }

    .description {
        width: calc(100% - 81px);
        padding-left: 25px;
    }

    .description h2 {
        font-family: 'Poppins',sans-serif;
        font-size: 28px;
        font-weight: 600;
        color: #562C2C;
    }

    .description p {
        font-family: 'Poppins',sans-serif;
        font-size: 18px;
        font-weight: 400;
        color: #562C2CCC;
    }

    .content {
        max-width: 65%;
        padding: 0 15px;
    }

    .image-container {
        padding: 0 15px;
    }

    .image-container img {
        width: 503px;
        border-radius: 10px;
    }

    h1 {
        color: #ff5733;
    }

    .features {
        display: flex;
        justify-content: space-around;
        padding: 80px 20px 80px 20px;
    }

    .feature {
        text-align: center;
    }

    .feature h3 {
        font-family: 'Poppins',sans-serif;
        font-size: 24px;
        font-weight: 500;
        color: #562C2C;
    }

    .feature p {
        font-family: 'Poppins',sans-serif;
        font-size: 18px;
        font-weight: 400;
        color: #562C2CCC;
    }
    
    .icon {
        font-size: 24px;
        color: #00d1b2;
    }

    img.image-icon-image {
        width: 58px;
        height: 58px;
        object-fit: cover;
        margin-bottom: 16px;
    }
</style>