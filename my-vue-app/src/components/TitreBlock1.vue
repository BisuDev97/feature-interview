<template>
    <div class="wrapper-titre-bloc-1">
        <div class="title-container">
            <span class="title">Titre Bloc 1</span>
        </div>
        <div class="name-container">Sous-titre Bloc 1</div>
        <div class="card-container">
            <div class="card">
                <img alt="Case Title" class="image-case-title" src="@/assets/image1.png"/>
                <div class="card-content">
                    <span class="card-category">Case Title</span>
                    <h3 class="card-title">Case sous-titre</h3>
                    <p class="card-description">
                        Chaque sentier vous conduit à des panoramas époustouflants, chaque instant...
                    </p>
                    <a href="#" class="card-button">Forfait 1 <img alt="Arrow Up" class="image-arrow-up" src="@/assets/ArrowUpRight.png"/></a>
                </div>
            </div>

            <div class="card card-middle">
                <img alt="Case Title" class="image-case-title" src="@/assets/image2.png"/>
                <div class="card-content">
                    <span class="card-category">Case Title</span>
                    <h3 class="card-title">Case sous-titre</h3>
                    <p class="card-description">
                        Chez BASIC, la pêche est une alliance entre passion et respect...
                    </p>
                    <a href="#" class="card-button">Forfait 2 <img alt="Arrow Up" class="image-arrow-up" src="@/assets/ArrowUpRight.png"/></a>
                </div>
            </div>

            <div class="card">
                <img alt="Case Title" class="image-case-title" src="@/assets/image3.png"/>
                <div class="card-content">
                    <span class="card-category">Case Title</span>
                    <h3 class="card-title">Case sous-titre</h3>
                    <p class="card-description">
                        BASIC vous guide à travers des territoires authentiques...
                    </p>
                    <a href="#" class="card-button">Forfait 3 <img alt="Arrow Up" class="image-arrow-up" src="@/assets/ArrowUpRight.png"/></a>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .wrapper-titre-bloc-1 {
        max-width: 1270px;
        padding: 80px 15px;
        margin: 0 auto;
    }

    .title-container {
        display: flex;
        align-items: center;
        justify-content: center;
        position: relative;
        width: 100%;
    }

    .title-container::before,
    .title-container::after {
        content: "";
        flex: 1;
        height: 2px;
        background-color: #BBBBBB;
    }

    .title {
        padding: 0 30px;
        font-size: 52px;
        font-weight: 600;
        color: #F2542D;
        text-transform: uppercase;
        font-family: 'Poppins', sans-serif;
    }

    .name-container {
        font-size: 24px;
        font-weight: 400;
        color: #562C2C;
        letter-spacing: 0.25px;
        font-family: 'Poppins', sans-serif;
        text-align: center;
        margin-bottom: 40px;
    }

    .card-container {
        display: flex;
        justify-content: space-between;
        gap: 24px;
        max-width: 100%;
        margin: 0 auto;
        padding-top: 40px;
    }

    .card {
        background: #fff;
        border-radius: 16px;
        overflow: hidden;
        flex: 1;
        transition: transform 0.3s ease-in-out;
        border: none;
    }

    .card:hover {
        transform: translateY(-5px);
    }

    .card-middle {
        transform: translateY(-45px); /* Điều chỉnh chiều cao của item giữa */
    }

    .card-middle:hover {
        transform: translateY(-50px); /* Điều chỉnh chiều cao của item giữa */
    }

    .card img {
        width: 100%;
        object-fit: cover;
    }

    .card-content {
        padding-top: 24px;
    }

    .card-category {
        font-size: 20px;
        color: #F2542D;
        font-weight: 500;
        font-family: "Poppins",sans-serif;
    }

    .card-title {
        font-size: 28px;
        color: #562C2C;
        font-weight: 800;
        font-family: "Poppins",sans-serif;
        margin-top: 4px;
    }

    .card-description {
        font-size: 17px;
        color: rgba(86, 44, 44, 0.8);
        font-weight: 400;
        font-family: "Poppins",sans-serif;
        padding: 16px 0 24px 0;
        margin-bottom: 0;
    }

    .card-button {
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 8px 15px;
        border: 1.5px solid #562C2C4D;
        border-radius: 333px;
        text-decoration: none;
        font-size: 18px;
        color: #562C2C;
        font-weight: 500;
        transition: 0.3s;
        width: 249px;
        font-family: "Poppins",sans-serif;
        height: 44px;
    }

    .card-button img {
        margin-left: 8px;
    }

    .card-button:hover {
        background-color: #333;
        color: #fff;
    }

    .card img.image-arrow-up {
        width: 24px;
        height: 24px;
    }
</style>