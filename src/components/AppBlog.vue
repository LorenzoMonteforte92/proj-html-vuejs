<script>
    export default {
        name: 'AppBlog',

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
        <div class="container pt-5">
            <div class="row justify-content-center">
                <div class="col-12 d-flex justify-content-center flex-column mb-5">
                    <div class="ps-4 text-center" ><img src="../assets/img/blog.png" alt=""></div>
                    <h2 class="text-center" >Latest from the Blog</h2>
                </div>
                <div class="col d-flex flex-column justify-content-center">
                    <div class="card" style="width: 18rem;">
                        <img src="../assets/img/artist-blog-03-480x356.jpeg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <small class="card-text text-start ">ARTIST</small>
                            <h6 class="card-text text-start my-3" >Brush Stroke Energize Trees in Paintings</h6>
                            <small class="card-text me-5"><i class="fa-regular fa-calendar"></i> May 15, 2020</small>
                            <small class="card-text"><i class="fa-regular fa-eye"></i> 688 views</small>
                        </div>
                    </div>
                </div>
                <div class="col-6 d-flex justify-content-center position-relative">
                    <div class=" ms-card card position-relative" style="width: 70%;">
                        <img src="../assets/img/artist-blog-02-500x680.jpg" class="card-img-top" alt="...">
                        <div class="card-body position-absolute">
                            <small class="card-text text-start text-white ">ARTIST</small>
                            <h3 class="card-text text-start text-white my-3" >Connection Between Self-Portraits and Identity</h3>
                            <small class="card-text text-white me-5"><i class="fa-regular fa-calendar"></i> May 15, 2020</small>
                            <small class="card-text text-white"><i class="fa-regular fa-eye"></i> 397 views</small>
                        </div>
                    </div>
                </div>
                <div class="col position-relative">
                    <div class="card ms-small-card position-absolute" style="width: 18rem;">
                        <img src="../assets/img/artist-blog-01-480x356.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <small class="card-text text-start">ARTIST</small>
                            <h6 class="card-text text-start my-3" >Pocket-sized Notebooks Hold Miniature Paintings</h6>
                            <small class="card-text me-5"><i class="fa-regular fa-calendar"></i> May 15, 2020</small>
                            <small class="card-text"><i class="fa-regular fa-eye"></i> 603 views</small>
                        </div>
                    </div>
                </div>
                <div class="text-center my-5" >Get into details now? <span><a class="blog-link  fw-bold" href="#">View all posts <i class="fa-solid fa-arrow-right"></i></a></span></div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

    section{
        background-color: #F5F7FA;
        background-image: url('../assets/img/maxcoach-shape-14.png'), url('../assets/img/maxcoach-shape-05.png'), url('../assets/img/paint.png'), url('../assets/img/circle.png');
        background-repeat: no-repeat;
        background-position: 50%, 38% 25%, 70% 90%, 10% 25% ;

    }

    
   
    .ms-card{
    
        .card-body{
            bottom: 0;
        }
        img{
            width: 100%;
        }
    }

    .ms-small-card{
        top: 6%;
    }

    .blog-link{
        color: #EF6F31;
    }
</style>