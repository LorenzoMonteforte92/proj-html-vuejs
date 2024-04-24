<script>
    export default {
        name: 'AppEvents',

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
            <div class="row justify-content-center">
                <div class="col-10 d-flex flex-wrap gap-3 row-gap-3">
                    <div class="card flex-row" style="width: calc(100% / 2 - 1rem);">
                        <img src="../assets/img/artist-event-04-250x300.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <small class="card-text text-start ">ARTIST</small>
                            <h6 class="card-text text-start my-3" >Brush Stroke Energize Trees in Paintings</h6>
                            <small class="card-text me-5"><i class="fa-regular fa-calendar"></i> May 15, 2020</small>
                        </div>
                    </div>

                    <div class="card flex-row" style="width: calc(100% / 2 - 1rem);">
                        <img src="../assets/img/artist-event-03-250x300.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <small class="card-text text-start ">ARTIST</small>
                            <h6 class="card-text text-start my-3" >Brush Stroke Energize Trees in Paintings</h6>
                            <small class="card-text me-5"><i class="fa-regular fa-calendar"></i> May 15, 2020</small>
                        </div>
                    </div>

                    <div class="card flex-row" style="width: calc(100% / 2 - 1rem);">
                        <div class="card-body">
                            <small class="card-text text-start ">ARTIST</small>
                            <h6 class="card-text text-start my-3" >Brush Stroke Energize Trees in Paintings</h6>
                            <small class="card-text me-5"><i class="fa-regular fa-calendar"></i> May 15, 2020</small>
                        </div>
                        <img src="../assets/img/artist-event-02-250x300.jpg" class="card-img-top" alt="...">
                    </div>

                    <div class="card flex-row" style="width: calc(100% / 2 - 1rem);">
                        <div class="card-body">
                            <small class="card-text text-start ">ARTIST</small>
                            <h6 class="card-text text-start my-3" >Brush Stroke Energize Trees in Paintings</h6>
                            <small class="card-text me-5"><i class="fa-regular fa-calendar"></i> May 15, 2020</small>
                        </div>
                        <img src="../assets/img/artist-event-01-250x300.jpg" class="card-img-top" alt="...">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    .card{
        border: none;
        img{
            width: 40%;
        }
    }

    .card-body{
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
</style>