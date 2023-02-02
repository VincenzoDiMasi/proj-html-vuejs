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
          <h6 class="grey-title">DREAM WITH MAXCOACH</h6>
          <div>
            <h1>Construct A <span class="highlighted">Stunning</span>  <br> Career Perspective</h1>        
          </div>
          <div class="menu-item-green d-flex justify-content-between mt-4">
            <p>Multiple Platforms Supported for Teaching & Studying </p> <a href="#"><i class="fa-solid fa-circle-minus text-white"></i></a>
          </div>
          <div class="text-item">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Placeat, quae excepturi! Numquam consequatur aspernatur, vitae necessitatibus quod earum dignissimos. Cupiditate excepturi sed dolorem quia quisquam facere quasi delectus tenetur adipisci.</p>
          </div>
          <div class="menu-item d-flex justify-content-between mt-4">
            <p>Multiple Course Partecipatiom at the Same Time </p> <a href="#"><i class="fa-solid fa-circle-plus"></i></a>
          </div>
          <div class="menu-item d-flex justify-content-between mt-4">
            <p>Track Study Progress & Deliver Prompt Feedback </p> <a href="#"><i class="fa-solid fa-circle-plus"></i></a>
          </div>
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
    .menu-item-green {
    background-color: #20AD96;
    border-radius: 10px 10px 0 0 ;
    border: 1px solid #20AD96;
    height: 50px;
    padding: 10px;

    
    
    
    p {
      color: white;
      font-weight: bold;

    }
  }

  .text-item {
    box-shadow: 2px 4px #dcdbdb;
    background-color: #f8f8f8;
    border-radius: 0 0 10px 10px;
    padding: 10px;

    p{
      color: #696969;
      font-size: 12px;
    }
  }

.menu-item {
    height: 50px;
    padding: 10px;
    box-shadow: 2px 4px #dcdbdb;

    border: 1px solid white;
    background-color: #f8f8f8;
    

    p,.fa-circle-plus {
      color: #696969;
      font-weight: bold;

    }
    }

}




</style>