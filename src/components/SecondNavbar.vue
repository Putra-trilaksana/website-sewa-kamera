<template>
    <div class="top-bar d-flex justify-content-center gap-5 mt-2">
        <a href="" class="item">
            <img src="../assets/delivery-box.png" alt="">
            <span>ALL PRODUCT</span>
        </a>
        <a href="" class="item">
            <img src="../assets/new-product.png" alt="">
            <span>NEW PRODUCT</span>
        </a>
        <a href="" class="item">
            <img src="../assets/camera.png" alt="">
            <span>KAMERA</span>
        </a>
        <a href="" class="item">
            <img src="../assets/camera-lens.png" alt="">
            <span>LIGHTING</span>
        </a>
        <a href="" class="item">
            <img src="../assets/camera-tripod.png" alt="">
            <span>TRIPOD</span>
        </a>
        <a href="" class="item">
            <img src="../assets/lan.png" alt="">
            <span>ACCESSORIES</span>
        </a>
        <a href="" class="item">
            <img src="../assets/light.png" alt="">
            <span>ACCESSORIES</span>
        </a>
        <a href="" class="item">
            <img src="../assets/mixer.png" alt="">
            <span>ACCESSORIES</span>
        </a>
        <a href="" class="item">
            <img src="../assets/multimedia.png" alt="">
            <span>ACCESSORIES</span>
        </a>
    </div>
</template>

<style scoped>
    .item {
        display: flex;
        flex-direction: column;
        text-decoration: none;
    }

    .item img {
        width: 50px;
        margin: 0 auto;
    }

    .item span {
        font-size: 12px;
        font-weight: 600;
        color: black;
    }

    .top-bar {
        box-shadow: 0px 2px 3px rgba(81, 81, 81, .3);
        padding: 5px 0;
    }

    .item:hover {
        transform: translateY(-5px);
        color: orange;
    }

</style>