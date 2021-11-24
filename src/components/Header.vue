<template>
        <div class="header d-flex">
            <nav class="nav-top">
                <div class="logo-container">
                    <img src="@/assets/img/logo-light.png" alt="">
                </div>
                <ul>
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">COURSES</a></li>
                    <li><a href="#">INSTRUCTORS</a></li>
                    <li><a href="#">EVENTS</a></li>
                    <li><a href="#">PAGES</a></li>
                    <li><a href="#">ELEMENTS</a></li>
                </ul>
                <div class="icon-nav">
                    <img src="@/assets/svg/svg-0.svg" class="w-25" alt="">
                    <img src="@/assets/svg/svg-0.svg" class="w-25" alt="">
                    <img src="@/assets/svg/svg-0.svg" class="w-25" alt="">
                </div>
            </nav>
        </div>
</template>

<script>
export default {
    
}
</script>

<style>

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.header{
    flex-direction: row;
    width: 100%;
    margin: auto;
    background-color: aquamarine;
}

.nav-top li, .nav-top a{
    display: flex;
    list-style: none;
    text-decoration: none;
}

.header-container{
    background-color: aquamarine;

}


.nav-top 

/*Importare style utilities.scss */
.m-auto{
    margin: auto;
}

.w-25{
    width: 5%;
}

.p-relative{
    position: relative;
}

.p-absolute{
    position: absolute;
}

.col-4{
    width: calc(100% /12 * 4);
}

.col-8{
    width: calc(100% /12 * 8);
}

.d-flex{
    display: flex;
}

.d-inline-block{
    display: inline-block;
}

.text-center{
    text-align: center;
}

.text-right{
    text-align: right;
}

.m-bot-25{
    margin-bottom: 50px;
}

.m-bot-header{
    margin-bottom: 15px;
}

.text-l-grey{
    color: lightgrey;
}
.text-grey{
    color: grey;
}

.text-white{
    color: white;
}

.text-red{
    color: red ;
}

.text-small{
    font-size: 12px;
}

.text-ultra-small{
    font-size: 10px;
}

.m-top{
    margin-top: 50px;
}

.overflow{
    overflow: auto;
}

.shrink{
    flex-shrink: 0;
}
</style>