<script>

    import NewProduct from '../assets/new-product.png'
    import Camera from '../assets/camera.png'
    import Lensa from '../assets/camera-lens.png'
    import Tripod from '../assets/camera-tripod.png'
    import Lighting from '../assets/light.png'
    import Mixer from '../assets/multimedia.png'
    import AllProduct from '../assets/delivery-box.png'
    import Aksesoris from '../assets/lan.png'

    export default {
        data:() => ({
            cards: [
                {id: 1, title: 'PRODUCT BARU', src: NewProduct},
                {id: 2, title: 'SEMUA PRODUK', src: AllProduct},
                {id: 3, title: 'KAMERA', src: Camera},
                {id: 4, title: 'LENSA', src: Lensa},
                {id: 5, title: 'TRIPOD', src: Tripod},
                {id: 6, title: 'LIGHTING', src: Lighting},
                {id: 7, title: 'MULTIMEDIA', src: Mixer},
                {id: 8, title: 'AKSESORIS', src: Aksesoris},
            ],
        }),
    }
</script>


<template>
    <div class="top-bar d-flex flex-col justify-content-center gap-5">
        <a href="" class="item"  v-for="card in cards" :key="card.id">
            <img :src="card.src" alt="Gambar">
            <span>{{card.title}}</span>
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
        width: 60px;
        margin: 0 auto;
    }

    .item span {
        font-size: 12px;
        font-weight: 600;
        color: black;
        margin: 0 auto;
    }

    .top-bar {
        box-shadow: 0px 2px 3px rgba(81, 81, 81, .3);
        padding: 5px 0;
        flex-direction: row;
    }

    .item:hover {
        transform: translateY(-5px);
        color: orange;
    }

</style>