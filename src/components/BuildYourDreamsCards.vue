<script>
export default {
  name: 'BuildYourDreamsCards',
  data() {
  return {};
},
props: {
  card: Object
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
        <div class="col">
            <div class="card" style="width: 18rem;">
              <img :src=" card.img " class="card-img-top" alt="...">
              <div class="card-body">
                <h5>{{ card.title }}</h5>
                <p class="card-text text-black">{{ card.text }}</p>
                <a class="text-prpl" href="#">{{ card.button }} <i class="fa-solid fa-arrow-right-long text-prpl"></i></a>
              </div>
            </div>
        </div>        
</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";

img {
  width: 140px;
  height: 160px;
  margin-left: auto;
  margin-right: auto;
}

.card {
  border: 0;
}

.text-prpl {
    color: $textPrimaryColorLight;
}
a:hover {
  background-color: $textPrimaryColorLight;
  color: white;
  border-radius: 20px;
  padding: 5px 7px;
}
</style>