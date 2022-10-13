<script>

export default {

}

</script>

<template>
        <div class="card-container">
            <div class="testi">
                <div class="d-flex flex-row">
                    <img src="../assets/profile.png" alt="" class="profile">
                    <div class="mt-4 ms-2">
                        <h5 class="name">Putra Trilaksana</h5>
                        <h6 class="job">Wedding Fotografer</h6> 
                    </div>
                </div>
                <p class="desc mt-4 px-3 d-flex justify-content-center">"Pengalaman Yang Luar Biasa, dengan harga yang terjangkau bisa merasakan pengalaman menggunakan kamera professional dengan hasil yang maksimal"</p>
            </div>
        </div>
</template>

<style scoped>

.testi {
    width: 300px;
    height: 300px;
    background-color: rgba(81, 81, 81, .2);
    padding: 10px;
    border-radius: 20px;
    box-shadow: 20px 20px 20px;
}

.profile {
    width: 100px;
}

.name {
    font-size: 20px;
    color: black;
}

.job {
    font-size: 13px;
    font-weight: 600;
    color: black;
}

.desc {
    font-size: 14px;
    font-weight: 700;
    text-align: center;
    color: black;
}
</style>