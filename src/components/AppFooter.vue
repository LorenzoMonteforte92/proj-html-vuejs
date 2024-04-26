<script>
    export default {
        name: 'AppFooter',
        
        props: ['positionNav'],
        props: ['explore'],
        props: ['info'],
        
        data(){
            return{
                
            }
        },
        methods: {
            
            }
        }
	

    
</script>


<template>
    <div class="container">
        <div class="row">
            <div class="col-3">
                <h6>Address</h6>
                <ul class="p-0">
                    <li v-for="singleInfo in info" ><a href="#">{{ singleInfo.title }}</a></li>
                </ul>
            </div>
            <div class="col-3">
                <h6>Explore</h6>
                <ul class="p-0">
                    <li v-for="singleExplore in info" ><a href="#">{{ singleExplore.title }}</a></li>
                </ul>
            </div>
            <div class="col-3">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Inventore rerum sint reprehenderit neque aperiam, dignissimos deserunt fuga exercitationem harum ut doloremque hic numquam ipsa minima ipsam delectus necessitatibus itaque totam.</div>
            <div class="col-3">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Inventore rerum sint reprehenderit neque aperiam, dignissimos deserunt fuga exercitationem harum ut doloremque hic numquam ipsa minima ipsam delectus necessitatibus itaque totam.</div>
        </div>
    </div>
</template>

<style scoped lang="scss">

</style>