<script>
import BuildYourDreamsCards from './BuildYourDreamsCards.vue';
export default {
  name: 'AppMain',
  components: {BuildYourDreamsCards,},
  data() {
    return {
      cardsBuildYourDream: [
                {
                    img: 'src/assets/img/home-5-image-box-01.png',
                    title: 'Idea Discussion',
                    text: 'Get teamed up with specialists who work and teach coding for years at famous universities.',
                    button: 'Start now',
                    id: 1
                },
                {
                    img: 'src/assets/img/home-5-image-box-02.png',
                    title: 'Web Development',
                    text: 'Learn to start building a webpage from scratch. You decide your own pace, course and speed.',
                    button: 'Start now',
                    id: 2
                },
                {
                    img: 'src/assets/img/home-5-image-box-03.png',
                    title: 'System Administration',
                    text: 'Learners are encouraged to study the mechanism and structure of system administration.',
                    button: 'Start now',
                    id: 3
                },
                {
                    img: 'src/assets/img/home-5-image-box-04.png',
                    title: 'Graphic Design',
                    text: 'Have a passion for graphic and arts? Show your talent with confidence and self-assertiveness.',
                    button: 'Start now',
                    id: 4
                },
                
               
            ]  
    };
  },
  methods: {
    // Your component methods 
  },
  computed: {
    // Computed properties 
  },
  created() {
    // Lifecycle hook 
  }
};
</script>

<template>
  <main>

    <section id="build-your-team" class="container text-center mt-5">
      <h6 class="grey-title">START LEARNING CODING LANGUAGES</h6>
      <div class="d-flex justify-content-center">
        <h1>Build Your Dream</h1>
        <h1 class="highlighted">TODAY</h1>
      </div>
      
      <div class="container d-flex mt-5 mb-5">
        <div class="row">
          <BuildYourDreamsCards v-for="card in cardsBuildYourDream" :card="card" :key="card.id"></BuildYourDreamsCards>
        </div>
      </div>
      
    </section>

    <section id="career" class="container my-5">
      <div class="row">
        <div class="col ms-5 underlay">
          <!-- <img class="underlay" src="../assets/img/underlay-shape-lilla.svg" alt=""> -->
          <img src="../assets/img/about-us-03-image-01.png" alt="">
          
        </div>
        <div class="col">

        </div>
      </div>


    </section>
  </main>
</template>

<style lang="scss" scoped>
section {
  min-height: 400px;
}
#career {

  .underlay {
    background-image: url('../assets/img/underlay-shape-lilla.svg');
    background-repeat: no-repeat;
    background-position: 0% 40%;
    background-size: 350px;

    img {
    margin-left: 120px;
    height: 450px;
  }
  }
  
}



</style>