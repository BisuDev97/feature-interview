<template>
    <section class="explore-section">
        <div class="description">
            <h2>Explorez Avec BASIC</h2>
            <p class="description-text">Dès Aujourd’hui</p>
            <p class="content">Lorem Ipsum is simply dummy text of the printing and typesetting industry...</p>
            <button class="explore-btn">Explorer</button>
        </div>
    </section>
</template>

<style scoped>
    .explore-section h2 {
        font-family: 'Poppins',sans-serif;
        font-size: 52px;
        font-weight: 600;
        color: #562C2C;
        margin-bottom: 0;
    }
    .explore-section .description-text {
        font-family: 'Poppins',sans-serif;
        font-size: 52px;
        font-weight: 600;
        color: #562C2C80;
        margin-bottom: 0;
    }
    .description {
        max-width: 672px;
        margin: 0 auto;
        padding: 0 15px;
    }
    .explore-section {
        text-align: center;
        padding: 70px 20px;
        background-image: url('@/assets/MaskGroupBanner.png'); /* Cập nhật đường dẫn ảnh */
        background-size: cover;
        background-position: center;
        color: #3d2928;
        font-weight: bold;
        height: 666px;
    }
    .explore-section p.content {
        font-size: 24px;
        font-weight: 400;
        color: #562C2C;
        font-family: 'Poppins',sans-serif;
        margin-bottom: 40px;
    }
    .explore-btn {
        background-color: #ff5733;
        color: #fff;
        padding: 10px 20px;
        font-size: 18px;
        border: none;
        border-radius: 20px;
        cursor: pointer;
        width: 150px;
        transition: background-color 0.3s ease-in-out; /* Thêm transition để mượt mà */
    }
    .explore-btn:hover {
        background-color: #e74c3c; /* Màu nền khi hover */
    }
</style>