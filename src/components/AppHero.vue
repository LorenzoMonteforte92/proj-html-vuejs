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
<div class="container-fluid hero ">
    <div class="row"></div>
</div>
</template>

<style scoped lang="scss">
.hero{
    // background: url('../assets/img/artist-shape-02.png') left no-repeat, url('../assets/img/artist-shape-01.png') 80% no-repeat contain, url('../assets/img/artist-hero-image-03.png') 20% no-repeat, ;
    background-image: url('../assets/img/artist-shape-02.png'), url('../assets/img/artist-shape-01.png'), url('../assets/img/artist-hero-image-03.png'), url('../assets/img/artist-shape-03.png'), url('../assets/img/paint.png'), ;
    background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
    background-position: left, 80%, 25% 100%, 1%, -8% 120% ;
    background-size: contain, contain, 9%, 13%, 35%;
    min-height: 380px;
    
}
</style>