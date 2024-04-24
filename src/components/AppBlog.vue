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
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex justify-content-center flex-column mb-5">
                    <div class="ps-4 text-center" ><img src="../assets/img/blog.png" alt=""></div>
                    <h2 class="text-center" >Latest from the Blog</h2>
                </div>
                <div class="col"></div>
                <div class="col-6 d-flex justify-content-center position-relative">
                    <div class="card position-relative" style="width: 70%;">
                        <img src="../assets/img/artist-blog-02-500x680.jpg" class="card-img-top" alt="...">
                        <div class="card-body position-absolute">
                            <small class="card-text text-start text-white ">ARTIST</small>
                            <h3 class="card-text text-start text-white my-3" >Connection Between Self-Portraits and Identity</h3>
                            <small class="card-text text-white me-5"><i class="fa-regular fa-calendar"></i> May 15, 2020</small>
                            <small class="card-text text-white"><i class="fa-regular fa-eye"></i> 397 views</small>
                        </div>
                    </div>
                </div>
                <div class="col"></div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">

    section{
        background-color: #F5F7FA;
        background-image: url('../assets/img/maxcoach-shape-14');
    }

    .card{
        .card-body{
            bottom: 0;
        }
        img{
            width: 100%;
        }
    }
</style>