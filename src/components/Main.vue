<template>
    <main class="p-25">
        <div class="card-container d-flex">
            <div v-for="card, i in cardList" :key="i" class="card p-card text-center col-1">
                <div class="img-card">
                    <img :src="card.img" class="m-bot" alt="">
                </div>
                <h5 class="">{{card.title}}</h5>
            </div>
        </div>

        <section class="minor-hero m-top">
            <h1 class="pb-15">The Trusted Name <br>
            for In-Home Tutoring.</h1>
            <p class="pb-20 ln-20">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aut molestiae architecto maxime tempora 
                perspiciatis minima laudantium rerum earum sunt placeat odio 
                pariatur, recusandae distinctio soluta, repudiandae sint dolor 
                corrupti. Itaque.
            </p>
            <a href="#" class="text-small btn">LEARN MORE</a>

            <div class="img-minor-hero p-relative">
                <img src="@/assets/img/h5-img-1.jpg" alt="">

                <a href="#" class="text-white text-center go-top p-absolute btn blue d-flex">
                    <i class="fas fa-chevron-up text-white"></i>
                    <p>TOP</p>
                </a>

            </div>
        </section>
    </main>
</template>

<script>
export default {
    name: 'Main',
    data(){
        return{
            cardList: [
                {
                    img:require("@/assets/img/h5-custom-icon-1.png"),
                    title: "Languages"
                },
                {
                    img:require("@/assets/img/h5-custom-icon-2.png"),
                    title: "Languages"
                },
                {
                    img:require("@/assets/img/h5-custom-icon-3.png"),
                    title: "Languages"
                },
                {
                    img:require("@/assets/img/h5-custom-icon-4.png"),
                    title: "Languages"
                },
                {
                    img:require("@/assets/img/h5-custom-icon-5.png"),
                    title: "Languages"
                },
                {
                    img:require("@/assets/img/h5-custom-icon-6.png"),
                    title: "Languages"
                },
            ]
        }
    }
}
</script>

<style lang="scss">
    @import "@/styles/app";
</style>