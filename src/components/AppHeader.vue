<script>
    export default {
        name: 'AppHeader',

        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>

<template>
    <div class="container-fluid">
        <div class="row header-top">
            <div class="col-12 d-flex py-2 justify-content-center align-items-center gap-4">
                Starts TOMORROW! Our bigget event of the year...
            <span class="fw-bold" ><i class="fa-regular fa-clock"></i> 00 : 00 : 00: 00</span>
            <button class="btn fw-bold text-white px-4">Get Started</button>
            </div>
        </div>
        <div class="row"></div>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

.header-top{
    background-color: #F5F5F5;

        .btn{
            background-color: $brand-secondary-color;
        }
}

.header-top{
    
}
</style>