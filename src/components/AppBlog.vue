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
                <div class="col-6 text-center d-flex ">
                    <!-- <div class="article-img " >
                        <img src="../assets/img/artist-blog-02-500x680.jpg" alt="">
                    </div>
                        <div class="article-txt text-start position-absolute" >
                            <small>fghfd</small>
                            <h3>dfghjhgdfghjkhgfdsdfghjkjhgfddfghjkjhgfdssdfghjklòlkjhgfdfds</h3>
                            <small class="me-2">dfghjhgfd</small>
                            <small>dfghjhgfds</small>
                        </div> -->
                    
                        <div class="card" style="width: 90%;">
                        <img src="../assets/img/artist-blog-02-500x680.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
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

    .article-txt{
        left: 5%;
        bottom: 0;
    }

    .article-img{
        height: 80%;

            img{
                width: 100%;
            }

    }
</style>