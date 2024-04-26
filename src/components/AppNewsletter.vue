<script>
    export default {
        name: 'AppNewsletter',

        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>

<template>
    <section class="p-5 my-5" >
        <div class="container">
            <div class="row text-white ">
                <div class="col-4">
                    <h1 class="m-0" >Newsletter to get in touch</h1>
                </div>
                <div class="col-6 d-flex align-items-center position-relative input-container fs-4">
                    <input type="mail">
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    section{
        background-color: #244186;
        background-image: url('../assets/img/artist-shape-color-paint-top-left.png'), url('../assets/img/artist-shape-color-paint-bottom-right.png');
        background-repeat: no-repeat ;
        background-position: 0%, right;
        background-size: contain;
    }


    input{
        border: none;
        border-bottom: 1px solid white;
        background-color: transparent;
        width: 100%;
        position: relative;
        color: white;
    }

    .input-container:after {
        position: absolute;
        right: 2%;
        content: '→';
        cursor: pointer;
}

    .fa-arrow-right{
        border-bottom: 1px solid white;
        
    }
</style>