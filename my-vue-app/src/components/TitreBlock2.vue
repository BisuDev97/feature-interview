<template>
    <div class="wrapper-titre-bloc-2">
        <div class="title-container">
            <span class="title">Titre Bloc 2</span>
        </div>
        <div class="wrapper-item-map">
            <div class="item-map">
                <img alt="Facebook" class="image-icon-social" src="@/assets/Mountains.png"/>
                <span>Activité 1</span>
            </div>
            <div class="item-map">
                <img alt="Facebook" class="image-icon-social" src="@/assets/FishingIcon.png"/>
                <span>Activité 2</span>
            </div>
            <div class="item-map">
                <img alt="Facebook" class="image-icon-social" src="@/assets/Crosshair.png"/>
                <span>Activité 3</span>
            </div>
        </div>
        <div class="wrapper-map">
            <img alt="Map" class="image-map" src="@/assets/map.png"/>
            <img alt="MapPinTarget" class="image-map-pin-target" src="@/assets/MapPinTarget.png"/>
            <img alt="MapPinFish" class="image-map-pin-fish" src="@/assets/MapPinFish.png"/>
            <img alt="MapPinMoutain" class="image-map-pin-mountain" src="@/assets/MapPinMoutain.png"/>
        </div>
    </div>
</template>

<style scoped>
    .wrapper-map {
        position: relative;
    }
    .item-map span {
        font-size: 20px;
        font-weight: 500;
        color: #562C2C;
        font-family: 'Poppins', sans-serif;
    }
    .wrapper-titre-bloc-2 {
        background-image: url('@/assets/TitreBlock2.png'); /* Cập nhật đường dẫn ảnh */
        background-size: cover;
        background-position: center;
        height: 969px;
        background-color: #FFF6F4;
    }

    .title-container {
        max-width: 1270px;
        padding: 80px 15px 10px;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: center;
        position: relative;
        width: 100%;
    }

    .wrapper-item-map {
        display: flex;
        width: 500px;
        justify-content: space-between;
        margin: 0 auto 30px auto;
    }

    .item-map {
        width: 155px;
        height: 44px;
        border: 1px solid #F2542D80;
        border-radius: 40px;
        display: flex;
        align-items: center;
        text-align: center;
        background-color: #fff;
        justify-content: center;
        cursor: pointer;
    }

    img.image-icon-social {
        width: 28px;
        height: 28px;
        object-fit: contain;
        margin-right: 5px;
    }

    img.image-map {
        height: 698px;
        max-width: 1240px;
        display: block;
        margin: 0 auto;
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
    img.image-map-pin-mountain {
        position: absolute;
        top: 41%;
        left: 39%;
        width: 32px;
        height: 42px;
    }
    img.image-map-pin-target {
        position: absolute;
        top: 57%;
        left: 38%;
        width: 32px;
        height: 42px;
    }
    img.image-map-pin-fish {
        position: absolute;
        top: 46%;
        left: 50%;
        width: 32px;
        height: 42px;
    }
</style>