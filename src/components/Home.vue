<script>
import HeroCarousel from './HeroCarousel.vue';
import ItemList from './ItemList.vue';
import Testimoni from './Testimoni.vue';
export default {
    components: { HeroCarousel, ItemList, Testimoni }
}
</script>

<template>
    <div class="container">
        <HeroCarousel />
        <ItemList />
        <Testimoni />
    </div>
</template>

<style scoped>

.list-item {
    margin-top: 20px;
}

.list-item-title {
    font-family: 'Montserrat', sans-serif;
    font-size: 25px;
    font-weight: 600;
    margin: 0 auto;
    opacity: .9;
}

.card {
    border: none;
}

.card:hover {
    box-shadow: 2px 2px ;
}

.card-title{
    display: flex;
    font-size: 15px;
    justify-content: center;
}

.card-price{
    display: flex;
    font-size: 13px;
    font-weight: 700;
    justify-content: center;
}

.card-price:last-child {
    color: red;
}

.button {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
}

.button-wa {
    padding: 2px 5px;
    background-color: green;
    color: white;
    border-radius: 8px;
    padding-bottom: 5px;
}

.button-wa:hover {
    color: white;
    transform: translateY(-5px);
}

.button-like:hover {
    color: white;
    transform: translateY(-5px);
}

.button-like {
    padding: 2px 5px;
    background-color: black;
    color: white;
    border-radius: 8px;
    padding-bottom: 5px;
}


</style>