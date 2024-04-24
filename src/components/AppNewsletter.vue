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
                <div class="col-6 d-flex align-items-center">
                    <input type="mail">
                    <i class="fa-solid fa-arrow-right"></i>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    section{
        background-color: #244186;
    }

    input{
        border: none;
        border-bottom: 1px solid white;
        background-color: transparent;
        width: 100%;

    }

    .fa-arrow-right{
        border-bottom: 1px solid white;
        
    }
</style>