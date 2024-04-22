<script>
    export default {
        name: 'AppHeader',
        props: ['navLinks'],

        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>

<template>
    <div class="container-fluid">
        <div class="row header-top">
            <div class="col-12 d-flex py-2 justify-content-center align-items-center gap-4">
                Starts TOMORROW! Our bigget event of the year...
            <span class="fw-bold" ><i class="fa-regular fa-clock"></i> 00 : 00 : 00: 00</span>
            <button class="btn fw-bold text-white px-4">Get Started</button>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="row header-bottom py-3">
            <div class="col-3 d-flex  align-items-center"><img src="../assets/img/dark-logo.png" alt=""></div>
            <div class="col-6 d-flex justify-content-center align-items-center">
                <ul class="p-0 d-flex justify-content-center align-items-center gap-5 m-0" >
                    <li  v-for="singleLink in navLinks" class="d-flex align-items-center gap-2" ><a href="#">{{ singleLink.title }}</a> <i class="fa-solid fa-chevron-down"></i></li>
                </ul>
            </div>
            <div class="col-3 d-flex justify-content-end align-items-center ms-font-color gap-4">
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-linkedin"></i>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

.header-top{
    background-color: #F5F5F5;

        .btn{
            background-color: $brand-secondary-color;
        }
}

.header-bottom{

    img{
        max-width: 55%;
    }
    .ms-font-color{
        color: #696969;
    }

    .fa-chevron-down{
        font-size: x-small;
    }
}
</style>