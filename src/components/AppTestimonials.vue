<script>
    export default {
        name: 'AppTestimonials',

        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>

<template>
                                                       <!-- completare scritte -->
    <section>
        <div class="container-fluid p-5">
            <div class="row justify-content-center my-4">
                <div class="col-5 d-flex justify-content-center flex-column">
                    <div class="ps-4 text-center" ><img src="../assets/img/testimonials.png" alt=""></div>
                    <h2 class="text-center" >Why do people love me?</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-12 d-flex gap-5">
                    <div class="card " style="width: calc(100% / 3);">
                        <div class="card-body">
                            <h5 class="card-title">It's a choice of quality for people with special needs</h5>
                            <p class="card-text ">I'm a very strict person so I require everithing to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys got me.</p>
                        </div>
                        <div class="card-body  d-flex align-items-center gap-3" >
                            <div class=" ms-card-img" ><img class="rounded-circle "  src="../assets/img/artist-testimonial-avatar-02.jpg" alt=""></div>
                            <div>
                                <h6>Florence Themes</h6>
                                <small>/ Multimedia Admin</small>
                            </div>
                        </div>
                    </div>

                    <div class="card " style="width: calc(100% / 3);">
                        <div class="card-body">
                            <h5 class="card-title">High level of efficiency nd scientific teaching methods</h5>
                            <p class="card-text ">I'm a very strict person so I require everithing to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys got me.</p>
                        </div>
                        <div class="card-body  d-flex align-items-center gap-3" >
                            <div class=" ms-card-img" ><img class="rounded-circle "  src="../assets/img/artist-testimonial-avatar-04.jpg" alt=""></div>
                            <div>
                                <h6>Mina Hollace</h6>
                                <small>/ Freelancer</small>
                            </div>
                        </div>
                    </div>

                    <div class="card " style="width: calc(100% / 3);">
                        <div class="card-body">
                            <h5 class="card-title">It's a choice of quality for people with special needs</h5>
                            <p class="card-text ">I'm a very strict person so I require everithing to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys got me.</p>
                        </div>
                        <div class="card-body  d-flex align-items-center gap-3" >
                            <div class=" ms-card-img" ><img class="rounded-circle "  src="../assets/img/artist-testimonial-avatar-01.jpg" alt=""></div>
                            <div>
                                <h6>Florence Themes</h6>
                                <small>/ Multimedia Admin</small>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

    section{
        background-color: #FAF8F6;
    }

    .card{
        border: none;

            .ms-card-img {
                width: 20%;
                    img{
                        width: 100%
                    }
                
            }
    }

    .ms-card{
        opacity: 0.5;
    }

    .ms-active-card{
        opacity: 1;
    }

</style>