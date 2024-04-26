<script>
import { store } from '../store.js';
    export default {
        name: 'AppFooter',
        props: ['info'],
        
        data(){
            return{
                store
            }
        },
        methods: {
            
            }
        }
	

    
</script>


<template>
    <div class="container">
        <div class="row">
            <div class="col-4">
                <h6>Address</h6>
                <ul class="p-0">
                    <li class="pb-2" v-for="singlePosition in store.positionLinks" ><a href="#">{{ singlePosition.title }}</a></li>
                </ul>
            </div>
            <div class="col-2">
                <h6>Explore</h6>
                <ul class="p-0">
                    <li v-for="singleExplore in store.exploreLinks" ><a href="#">{{ singleExplore.title }}</a></li>
                </ul>
            </div>
            <div class="col-2">
                <h6>Information</h6>
                <ul class="p-0">
                    <li v-for="singleExplore in info" ><a href="#">{{ singleExplore.title }}</a></li>
                </ul>
            </div>
            <div class="col-4">
                <h6>Instagram <span class="mail" >@maxCoach</span></h6>
                <div class="footer-img d-flex gap-3" >
                    <!-- <div><img src="../assets/img/artist-blog-03-480x356.jpeg" alt=""></div>
                    <div><img src="../assets/img/artist-event-03-250x300.jpg" alt=""></div>
                    <div><img src="../assets/img/artist-event-02-250x300.jpg" alt=""></div> -->
                    <div class="card" style="width: calc(100% / 3)">
                        <img src="../assets/img/artist-blog-03-480x356.jpeg" class="card-img-top" alt="...">
                    </div>
                    <div class="card" style="width: calc(100% / 3)">
                        <img src="../assets/img/artist-event-03-250x300.jpg" class="card-img-top" alt="...">
                    </div>
                    <div class="card" style="width: calc(100% / 3)">
                        <img src="../assets/img/artist-event-02-250x300.jpg" class="card-img-top" alt="...">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

    .mail{
        color: $brand-secondary-color
    }

    .card{
        border: none;
        img{
            width: 100%;
            height: 80%;
            object-fit: cover;
        }
    }
</style>