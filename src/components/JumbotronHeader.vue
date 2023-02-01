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
                    button: 'Download free E-book',
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
    <div class="container">
        <div class="row justify-content-between">
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
#jumbotron {
    background-image: url("../assets/img/jumbo-overlay.svg");
    background-repeat: no-repeat;
    background-color: #F5F1ED;
    min-height: 500px;
    
    // display: flex;
    // align-items: center;
    // transform: rotate(180deg)
    
    img{
        height: 450px;
        margin-left: 25%;
    }
    
}
</style>