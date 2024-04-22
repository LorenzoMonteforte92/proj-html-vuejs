<script>
    export default {
        name: 'AppHero',

        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>

<template>
<div class="container-fluid hero position-relative">
    <div class="col-4 hero-txt position-absolute d-flex flex-column text-center">
        <h1>Artist coaching and mentoring might be for you</h1>
        <button class="btn fw-bold text-white px-4">Get Started</button>
    </div>
    <div class="artist-hero position-absolute" ><img src="../assets/img/artist-hero-image-04.jpg" alt="artist image"></div>
    
</div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
.hero{
    // background: url('../assets/img/artist-shape-02.png') left no-repeat, url('../assets/img/artist-shape-01.png') 80% no-repeat contain, url('../assets/img/artist-hero-image-03.png') 20% no-repeat, ;
    background-image: url('../assets/img/artist-shape-02.png'), url('../assets/img/artist-shape-01.png'), url('../assets/img/artist-hero-image-03.png'), url('../assets/img/artist-shape-03.png'), url('../assets/img/paint.png'), url('../assets/img/artist-shape-04.png'), url('../assets/img/artist-shape-05.png'), url('../assets/img/artist-shape-03.png') ;
    background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
    background-position: left, 90% 0%, 25% 100%, 1%, -8% 120%, 90% 12%, 95% 100%, 78% 110%;
    background-size: contain, 30%, 9%, 13%, 35%, 7%, 18%, 10%;
    min-height: 380px;
    
}

.hero-txt{
   top: 50%;
   left: 50%;
   transform: translate(-50%, -50%);
   .btn{
            background-color: $brand-secondary-color;
            margin: 0 auto;
        }
}

.artist-hero{
    max-width: 15%;
    right: 15%;
    top: 15%;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    img{
        width: 100%;
    }
}
</style>