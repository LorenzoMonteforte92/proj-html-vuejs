<script>
    export default {
        name: 'AppCourses',

        data(){
            return{
                cardInfo: [
                    {
                        img: 'artist-course-08-480x480.jpg',
                        price: '$18.00',
                        title: 'The Acrilic Painting Academy',
                        lessons: '4 Lessons',
                        students: '50 Students',
                        over: false
                    },
                    {
                        img: 'artist-course-07-480x480.jpg',
                        price: '$21.00',
                        title: 'Drawing and Shading: Complete Course',
                        lessons: '14 Lessons',
                        students: '50 Students',
                        over: false
                    },
                    {
                        img: 'artist-course-06-480x480.jpg',
                        price: '$19.00',
                        title: 'The color Theory for Digital Artist',
                        lessons: '7 Lessons',
                        students: '50 Students',
                        over: false
                    },
                    {
                        img: 'artist-course-05-480x480.jpg',
                        price: '$35.00',
                        title: 'Ultimate Guide to Digital Sketching for Beginners',
                        lessons: '14 Lessons',
                        students: '50 Students',
                        over: false
                    },
                    {
                        img: 'artist-course-04-480x480.jpg',
                        price: '$19.00',
                        title: 'Portrait Drawing The Smart Way',
                        lessons: '2 Lessons',
                        students: '50 Students',
                        over: false
                    },
                    {
                        img: 'artist-course-03-480x480.jpg',
                        price: '$19.00',
                        title: 'Mastering Watercolor Painting for Beginners',
                        lessons: '9 Lessons',
                        students: '50 Students',
                        over: false
                    },
                    {
                        img: 'artist-course-02-480x480.jpg',
                        price: '$25.00',
                        title: 'The Art & Science of Drawing',
                        lessons: '4 Lessons',
                        students: '50 Students',
                        over: false
                    },
                    {
                        img: 'artist-course-01-480x480.jpg',
                        price: '$22.00',
                        title: 'The Colored Pencil Drawing Course',
                        lessons: '6 Lessons',
                        students: '50 Students',
                        over: false
                    }
                ],

                
            }
        },
        methods: {
          makeOverCardAppear(overIndex){
            this.cardInfo[overIndex].over = !this.cardInfo[overIndex].over;
          }
            }
        }
	
    
</script>

<template>
    <section class="my-4" >
        <div class="container">
            <div class="row pb-4">
                <div class="col-12 d-flex flex-wrap gap-4 pb-5">
                    <div v-for="singleCard, index in cardInfo" 
                    class="card position-relative flex-grow-1" 
                    
                    style="width: calc(100% / 4 - 1.5rem);"
                    @mouseenter="makeOverCardAppear(index)"
                    @mouseleave="makeOverCardAppear(index)"
                    >
                        <img :src="`src/assets/img/${singleCard.img}`" class="card-img-top mb-4" alt="...">
                        <!-- normal card text -->
                        <div class="card-body"
                        :class="{'d-none' : singleCard.over}">
                            <div class="flex-grow-1 " >
                                <h6 class="card-price" >{{singleCard.price}}</h6>
                                <h6 class="mt-3" >{{singleCard.title}}</h6>
                            </div>
                            <div class="mt-3" >
                                <small class="me-4" >{{singleCard.lessons}}</small>
                                <small>{{singleCard.students}}</small>
                            </div>
                        </div>
                        <!-- /normal card text -->

                        <!-- over card text -->
                        <div :class="{'d-flex' : singleCard.over}"
                        class="card-body body-hover flex-column position-absolute">
                            <div class="flex-grow-1 " >
                                <h6 class="card-price" >{{singleCard.price}}</h6>
                                <h6 class="mt-3 mb-0" >{{singleCard.title}}</h6>
                            </div>
                            <div class="mt-3" >
                                <small class="me-4" >{{singleCard.lessons}}</small>
                                <small>{{singleCard.students}}</small>
                            </div>
                        </div>
                        <!-- /over card text -->
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

    section{
        background-image: url('../assets/img/artist-shape-01-copia.png');
        background-position: 100%;
    }

    .card{
        border: none;
    }


    .card-body{
        height: 100%;
    }

    .card-price{
        color: $brand-secondary-color;
    }

    .body-hover{
        border: solid 2px $brand-secondary-color;
        background-color: white;
        width: 90%;
        height: 30%;
        top: 50%;
        display: none;
    }
</style>