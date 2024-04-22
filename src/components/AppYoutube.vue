<script>
    export default {
        name: 'AppYoutube',

        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>

<template>
    <section class="py-4" >
        <div class="container">
            <div class="row ">
                <div class="col-12 d-flex justify-content-center position-relative">
                    <img  class="poster" src="../assets/img/artist-video-poster.jpg" alt="">
                    <img  class="youtube position-absolute" src="../assets/img/icon-youtube-play.png" alt="">
                    <img class="circle position-absolute" src="../assets/img/circle.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

section{
    background-image: url('../assets/img/maxcoach-shape-05.png'), url('../assets/img/maxcoach-shape-12.png'), url('../assets/img/paint.png');
    background-repeat: no-repeat;
    background-position: 18% -2%, 88% 100%, 0% 0%;
    background-size: auto, auto, 30% 40%

   
}

.col-12{
    .poster{
        box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
    }
}

.youtube{
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.circle{
    right: 0%;
    top: 20%;
}

</style>