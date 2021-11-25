<template>
    <header class="p-relative">
        <div id="overlay">
            <img src="@/assets/img/course-9-f-img.jpg" class="p-absolute" alt="">
        </div> 


        <!-- Inizio Nav -->
        <div class="nav-top d-flex m-bot-h">
            <div class="logo f-g">
                <img src="@/assets/img/logo-light.png" alt="">
            </div>
            <!-- da qui v-for per stampare i link -->
            <ul class="links d-flex f-g text-white">
                <li v-for="link, i in navList" :key="i"><a href="#">{{link}}</a></li>
                
            </ul>
            <!--  -->
            <div class="icons d-flex f-g text-white">
                <i class="fas fa-search"></i>
                <i class="fas fa-shopping-bag"></i>
                <i class="fas fa-bars"></i>
            </div>
        </div>
        
        <section class="hero-section text-center">
            <h1 class="m-bot text-white">Contemporary Ideas</h1>
            <p class="text-white p-bottom-50">Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis veritatis sequi dolorem! Est, ut laboriosam similique at adipisci 
                accusantium illo aut. Sunt esse minus assumenda, magnam 
                ab veniam iste commodi?
            </p>
            <a class="btn blue text-white">REGISTER NOW</a>
        </section>
        <div class="dot-menu text-white d-flex">
            <i class="far fa-circle"></i>
            <i class="far fa-circle"></i>
            <i class="far fa-dot-circle"></i>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
    data (){
        return {
            navList:[
                "HOME", 
                "COURSES", 
                "INSTRUCTORS", 
                "EVENTS", 
                "PAGES", 
                "EVENTS"
            ]
        }
    }
}
</script>

<style>


</style>