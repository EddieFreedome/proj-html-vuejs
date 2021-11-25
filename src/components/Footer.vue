<template>
    <footer class="">
        <div class="footer-menu d-flex p-bottom-50">
            <div class="bottom-col col1-4 d-flex pr-20 ln-20">
                <div class="logo f-g p-bottom-50  ">
                    <img src="@/assets/img/logo-light.png" alt="">
                </div>
                <p class="text-grey pb-20 ln-25">Providing Life Changing Experience Through Education.
                    Class That Fit Your Busy Life. Closer To Home
                </p>
                <div class="phone text-white d-flex pr-20 pb-20">
                    <i class="fas fa-phone-alt"></i>
                    <p class="text-small">1-677-124-44227</p>
                </div>
                <div class="phone text-white d-flex">
                    <i class="far fa-clock"></i>
                    <p class="text-small">Mon-Sat 8.00-18.00</p>
                </div>
            </div>
    
            <div class="bottom-col col1-4 d-flex pr-20 ln-20">
                
                <h2 class="text-white p-bottom-50">Popular Courses</h2>
                
                <div v-for="teacher, i in listFooter" :key="i">
                    <h4 class="text-grey">{{teacher.mansione}}</h4>
                    <p class="text-grey pb-20 ln-25">{{teacher.name}}
                    </p>
                </div>
        
            </div>
    
            <div class="bottom-col col1-4 d-flex pr-20 ln-20">
                
                <h2 class="text-white p-bottom-50">Support</h2>
                <div v-for="service, i in supportList" :key="i">
                    <a href="#" class="text-grey m-bot">{{service.service}}</a>
                </div>
            </div>
    
            <div class="bottom-col col1-4 d-flex pr-20 ln-20">
                
                <h2 class="text-white m-bot">Flexible Learning</h2>
                <div class="img-footer">
                    <img src="@/assets/img/footer-img-1.png" alt="">
                </div>
            
            </div>
        </div>

        <hr class="m-bot">
        
        <div class="references d-flex text-grey text-small">
            <div class="ref1 f-g d-flex">
                <p>Copyright 2017 @Mikado Themes</p>
            </div>
            <div class="ref2 d-flex"></div>
            <div class="ref3 f-g d-flex">
                <p>CALL +44 300 303 0266</p>
                <p class="mr-10">FOLLOW US </p>
                    <i class="fab fa-twitter mr-10"></i> <i class="fab fa-instagram mr-10"></i> <i class="fa fa-facebook-official" aria-hidden="true"></i>

            </div>
        </div>        
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    data(){
        return{
            listFooter:[
                {
                    mansione: "Business English",
                    name: "Preston Marshall"
                },
                {
                    mansione: "Business English",
                    name: "Preston Marshall"
                },
                {
                    mansione: "Social Computing",
                    name: "David Sanders"
                },
                {
                    mansione: "Learn Spanish",
                    name: "Jennie King"
                },
            ],
            supportList: [
                {
                   service: "User Dashboard",
                },
                {
                   service: "Contact Us",
                },
                {
                   service: "FAQ",
                },
                {
                    service:"Course Offer",
                },
                {
                    service:"Events"
                }
            ]
        }
    }
}
</script>

<style lang="scss">
    @import "@/styles/app";
</style>