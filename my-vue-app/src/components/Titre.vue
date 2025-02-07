<template>
    <div class="section-container">
        <div class="section-header">
            <h2 class="section-title">TITRE</h2>
            <a href="#" class="view-more">En Savoir Plus <img alt="Arrow Right" class="image-arrow-right" src="@/assets/ArrowRight.png"/></a>
        </div>
    </div>
    <div class="card-container">
            <div class="card">
                <img alt="Food Image" class="image-food-image" src="@/assets/image4.png"/>
                <div class="card-content">
                    <span class="card-category">Case title</span>
                    <h3 class="card-title">Case sous-titre</h3>
                    <p class="card-description">
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    </p>
                </div>
            </div>

            <div class="card">
                <img alt="Food Image" class="image-food-image" src="@/assets/image5.png"/>
                <div class="card-content">
                    <span class="card-category">Case title</span>
                    <h3 class="card-title">Case sous-titre</h3>
                    <p class="card-description">
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    </p>
                </div>
            </div>

            <div class="card">
                <img alt="Food Image" class="image-food-image" src="@/assets/image6.png"/>
                <div class="card-content">
                    <span class="card-category">Case title</span>
                    <h3 class="card-title">Case sous-titre</h3>
                    <p class="card-description">
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    </p>
                </div>
            </div>

            <div class="card">
                <img alt="Food Image" class="image-food-image" src="@/assets/image8.png"/>
                <div class="card-content">
                    <span class="card-category">Case title</span>
                    <h3 class="card-title">Case sous-titre</h3>
                    <p class="card-description">
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    </p>
                </div>
            </div>
        </div>
</template>

<style scoped>
    .section-container {
        max-width: 1270px;
        margin: 0 auto;
        padding: 0 15px;
    }

    .section-header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
        padding-top: 80px;
    }

    .section-title {
        font-size: 48px;
        font-weight: 600;
        color: #F2542D; /* Màu cam */
        text-transform: uppercase;
    }

    .view-more {
        font-size: 20px;
        color: #666666;
        font-weight: 500;
        text-decoration: none;
        display: flex;
        align-items: center;
        gap: 5px;
        transition: color 0.3s ease-in-out;
    }

    .view-more:hover {
        color: #E74C3C;
    }

    .view-more:hover .image-arrow-right {
        transform: translateX(5px); /* Dịch sang phải 5px */
    }

    img.image-arrow-right {
        width: 24px;
        height: 24px;
        transition: transform 0.3s ease-in-out; /* Thêm transition để mượt mà */
    }

    .card-container {
        display: flex;
        gap: 56px;
        padding-bottom: 10px;
        max-width: 1470px;
        overflow: hidden;
        margin: 0 0 0 auto;
    }

    .card {
        background: #fff;
        overflow: hidden;
        width: 340px;
        transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        flex-shrink: 0;
        border: none;
    }

    .card img {
        width: 100%;
        border-radius: 8px;
        height: 340px;
        object-fit: cover;
        transition: transform 0.3s ease-in-out;
    }

    .card-content {
        padding-top: 15px;
    }

    .card-category {
        font-size: 20px;
        color: #F2542D;
        font-weight: 500;
        display: block;
        font-family: 'Poppins',sans-serif;
    }

    .card-title {
        font-size: 28px;
        font-weight: 500;
        color: #222222;
        margin-bottom: 10px;
    }

    .card-description {
        font-size: 18px;
        color: #562C2CCC;
        line-height: 1.5;
        padding: 10px 10px 0 10px;
        border-left: 0.5px solid #BBBBBB;
        margin-left: 5px;
        display: -webkit-box;
        -webkit-line-clamp: 3;
        -webkit-box-orient: vertical;
        overflow: hidden;
        text-overflow: ellipsis;
    }
</style>