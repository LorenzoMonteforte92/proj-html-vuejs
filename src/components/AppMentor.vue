<script>
    export default {
        name: 'AppMentor',

        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>

<template>
<div class="container my-5">
    <div class="row justify-content-center">
        <div class="col-5 d-flex justify-content-center flex-column">
            <div class="text-center mb-4" ><img src="../assets/img/artist-quote-icon.png" alt=""></div>
            <h1 class="text-center" >I coach and mentor visual artists, like you, to Create Like You Mean It</h1>
            <div class="text-center mt-4" ><img src="../assets/img/MartinGarrix.png" alt=""></div>
        </div>
        <div class="col-5 mt-5 pt-5">
            <p>As a coach and mentor, my ultimate goal is to motivare visual artists towards inspired action. I help you get you back on track to being the productive, creative, meaningful and authentic artist you truly want to be. I support artists in crafting and living a creative life as well as feeling good about themselves and their art.</p>
            <p>As an artist and an educator for nearly 30 years, I understand what it takes to create</p>
            <button class="btn fw-bold px-4 py-2" >Get Started Today</button>
        </div>
    </div>
</div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
.btn{
    background-color: #FDF0EA;
    margin: 0 auto;
    color: $brand-secondary-color;
    font-size: small;
    }
</style>