<script>
    export default {
        name: 'AppCoaching',

        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>

<template>
    <section>
        <div class="container">
            <div class="row justify-content-center my-4">
                <div class="col-5 d-flex justify-content-center flex-column">
                    <div class="ps-4" ><img src="../assets/img/artist.png" alt=""></div>
                    <h2 class="text-center" >I understand what it takes to create. I can help you with</h2>
                </div>
            </div>
            <div class="row ps-5">
                <div class="col-3 ">
                    <div><img src="../assets/img/artist-box-image-01.png" alt=""></div>
                    <h5>Onine Courses</h5>
                    <p>Online art coaching now offers you a very powerful way to redesign your artist mind</p>
                </div>
                <div class="col-3 pt-5 ">
                    <div class="mb-3" ><img src="../assets/img/artist-box-image-02.png" alt=""></div>
                    <h5>One to one</h5>
                    <p>Getting the necessary clarity about the current state to help you improve your ability</p>
                </div>
                <div class="col-3 ">
                    <div class="pb-1" ><img src="../assets/img/artist-box-image-03.png" alt=""></div>
                    <h5>Anywhere</h5>
                    <p>Access to valuable and portable program wich allows you to set up and live anywhere you want</p>
                </div>
                <div class="col-3 pt-5 ">
                    <div class="mb-3" ><img src="../assets/img/artist-box-image-04.png" alt=""></div>
                    <h5>On Time</h5>
                    <p>Punctuality is our top priority because it's an essential criteria to assess a program quality</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">

    section{
        background-image: url('../assets/img/maxcoach-shape-03.png'), url('../assets/img/artist-shape-01-copia.png'), url('../assets/img/maxcoach-shape-13.png');
        background-repeat: no-repeat;
        background-position: 100%, -28% 30%, 110%;
        background-size: contain, 40%, 20%;
        
    }


    .col-3{
        h5{
            align-self: start;
        }
    }
</style>