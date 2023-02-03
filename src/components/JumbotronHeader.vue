<script>
import CardJumbotron from './CardJumbotron.vue'
export default {
    name: 'JumbotronHeader',
    components: {CardJumbotron},
  data() {
    return {
        cards: [
                {
                    title: 'Complete Your Dreams in Javas Programming',
                    text: 'Learn any coding program in distance and for a responsable fee. You do not have to struggle alone, you have got our assistance and help.',
                    button: '<i class="fa-solid fa-download text-white"></i> Download free E-book',
                    id: 1
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
  <section id="jumbotron">
    <!-- JUMBOTRON IMAGE -->
    <div class="wave"><img src="../assets/img/jumbo-overlay.svg" alt=""></div>
    <div class="container z-ind">
        <div class="row justify-content-between">

          <!-- JUMBOTRON CARD -->
            <div class="col-sm-4">

                <CardJumbotron v-for="card in cards" :card="card" :key="card.id"></CardJumbotron>
            </div>
            <div class="col-sm-8 ">
                
                    <img src="../assets/img/home-5-hero-image.png" alt="">
               
            </div>
        </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";

#jumbotron {
    // background-image: url("../assets/img/jumbo-overlay.svg");
    // background-repeat: no-repeat;
    background-color: $bgBeige;
    min-height: 500px;
    position: relative;
    overflow: hidden;
    z-index: 0;
    
    // display: flex;
    // align-items: center;
    // transform: rotate(180deg)

    .z-ind {
      z-index: 2;
      position: relative;
    }
    
.wave{
position: absolute;
bottom: -70px;
width: 100%;
z-index: 1;


img{
  width: 100%;
  transform: rotate(180deg) scaleX(-1);
  margin-left: 0;
  
}
}

    img{
        height: 450px;
        margin-left: 25%;
    }
    
}
</style>