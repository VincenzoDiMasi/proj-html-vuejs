<script>
export default {
  name: 'CardEvents',
  data() {
    return {
      // Your data properties 
    };
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
  <div  class="col">
          <div class="container">
            <div class="row event-card">
              <div class="col-8 text-start">
                <h6 class="grey-title"><i class="fa-solid fa-location-dot"></i>{{ card.gps }}</h6>
                <h4 class="text-black">{{ card.name }}</h4>
              </div>
              <div class="col-4">
                <h1 class="text-black">{{ card.day }}</h1>
                <h5 class="text-black">{{ card.month }}</h5>
                <a href="#" class="btn btn-green fw-bold my-3">{{ card.button }}</a>

               
              </div>
            </div>
          </div>
        </div>
</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";

.event-card {
  // border: 1px solid black;
  height: 200px;
  align-items: center;
  background-color: $bgSecondaryColor;
  margin-bottom: 22px;
  transition: 1s linear;


.fa-location-dot {
        margin-right: 10px;
    }

 }

 .event-card:hover {
  box-shadow: 0 14px 59px rgb(0 0 0 / 30%);
  transition: 1s linear;

 }

 .btn-green{
    background-color: $brandColor;
    color: white;

    .txt-wht {
      color: $bgMainColor;
      margin-left: 5px;
    }

    
}
</style>