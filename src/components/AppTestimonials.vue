<script>
    export default {
        name: 'AppTestimonials',

        data(){
            return{
              cardInfo: [
                {
                    title: `It's a choice of quality for people with special needs`, 
                    text: `I'm a very strict person so I require everithing to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys got me.`,
                    img: '02',
                    name: 'Florence Themes',
                    position: '/ Multimedia Admin',
                },
                {
                    title: 'High level of efficiency and scientific teaching methods',
                    text: `I'm free to learn at my own pace, follow my own schedule and choose the subject I want to learn from the Syllabus. Great study portal for people like me`,
                    img: '04',
                    name: 'Mina Hollace',
                    position: '/ Freelancer',
                },
                {
                    title: 'Professional team of specialists and passionate mentors at reach',
                    text: `I need to get a certification for English proficency and MaxCoach is my best choiche. Their tutors are smart and professional when dealing with students`,
                    img: '01',
                    name: 'Madley Pondor',
                    position: '/ IT Specialist',
                },
              ],
              activeItem: 1  
            }
        },
        methods: {
            activateCard(clickedIndex){
                this.activeItem = clickedIndex
            }
            }
        }
	

    //al click sulla card activeItem diventa uguale all'indice 
</script>

<template>
                                                       <!-- completare scritte -->
    <section>
        <div class="container-fluid p-5 my-5 ">
            <div class="row justify-content-center my-4">
                <div class="col-5 d-flex justify-content-center flex-column">
                    <div class="ps-4 text-center" ><img src="../assets/img/testimonials.png" alt=""></div>
                    <h2 class="text-center" >Why do people love me?</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-12 d-flex gap-5">
                    <div v-for="singleCard, index in cardInfo"
                    @click="activateCard(index)"
                    class="card ms-card" style="width: calc(100% / 3);"
                    :class="{'ms-active-card': index === activeItem}"
                    >
                        <div class="card-body">
                            <h5 class="card-title">{{ singleCard.title }}</h5>
                            <p class="card-text ">{{ singleCard.text }}</p>
                        </div>
                        <div class="card-body  d-flex align-items-center gap-3" >
                            <div class=" ms-card-img" ><img class="rounded-circle "  :src="`src/assets/img/artist-testimonial-avatar-${singleCard.img}.jpg`" alt=""></div>
                            <div>
                                <h6>{{ singleCard.name }}</h6>
                                <small>{{ singleCard.position }}</small>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

    section{
        background-color: #FAF8F6;
    }

    .card{
        border: none;

            .ms-card-img {
                width: 20%;
                    img{
                        width: 100%
                    }
                
            }
    }

    .ms-card{
        opacity: 0.5;
    }

    .ms-active-card{
        opacity: 1;
    }

  

</style>