<script>
import RedEpic from '../assets/red-epic.jpg'
import PanasonicLumix from '../assets/panasonic-lumic.jpg'
import SonyPwx from '../assets/soni-pwx.jpg'
export default {
    data:() => ({
        cards: [
            {id:1, title: 'RED EPIC', src:RedEpic, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:2, title: 'SONY PWX', src:SonyPwx, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:3, title: 'PANASOMIC LUMIX', src:PanasonicLumix, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:4, title: 'RED EPIC', src:RedEpic, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:5, title: 'SONY PWX', src:SonyPwx, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:6, title: 'PANASOMIC LUMIX', src:PanasonicLumix, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:7, title: 'RED EPIC', src:RedEpic, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:8, title: 'SONY PWX', src:SonyPwx, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:9, title: 'PANASOMIC LUMIX', src:PanasonicLumix, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},
            {id:10, title: 'RED EPIC', src:RedEpic, price:'Rp. 250.000/ hari', disc:'Rp. 500.000/ 3 hari'},

        ],
    }),
}
</script>


<template>
        <div class="list-item d-flex justify-content-center flex-column col-12">
            <h1 class="list-item-title">BEST PRODUCT</h1>
            <div class="d-flex justify-content-between col-12 gap-5 flex-wrap mt-5">
                <div class="card d-flex col-4" style="width: 13rem;" v-for="card in cards" :key="card.id">
                        <img :src="card.src" class="card-img-top" alt="...">
                        <div class="card-body">
                            <div class="card-text d-flex flex-column">
                                <h5 class="card-title justify-content-center">{{card.title}}</h5>
                                <p class="card-price d-flex justify-content-center mb-1">{{card.price}}</p>
                                <p class="card-price d-flex justify-content-center">{{card.disc}}</p>
                            </div>
                            <div class="button d-flex">
                            <a href="#" class="button-like">
                                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-heart" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                                <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                                <path d="M19.5 12.572l-7.5 7.428l-7.5 -7.428m0 0a5 5 0 1 1 7.5 -6.566a5 5 0 1 1 7.5 6.572"></path>
                                </svg>
                            </a>
                            <a href="#" class="button-wa">
                                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-whatsapp" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                                <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                                <path d="M3 21l1.65 -3.8a9 9 0 1 1 3.4 2.9l-5.05 .9"></path>
                                <path d="M9 10a0.5 .5 0 0 0 1 0v-1a0.5 .5 0 0 0 -1 0v1a5 5 0 0 0 5 5h1a0.5 .5 0 0 0 0 -1h-1a0.5 .5 0 0 0 0 1"></path>
                                </svg>
                            </a>
                            </div>
                    </div>
                </div>
            </div>
        </div>
</template>