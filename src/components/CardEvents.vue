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
                <h6><i class="fa-solid fa-location-dot"></i>{{ card.gps }}</h6>
                <h4>{{ card.name }}</h4>
              </div>
              <div class="col-4">
                <h1>{{ card.day }}</h1>
                <h5>{{ card.month }}</h5>
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