<script>
export default {
  name: 'CardCourses',
  data() {
    return {
      
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
    <div class="col mb-4">
        <div class="card" style="width: 18rem;">
          <img :src="card.mainImg" class="card-img-top" alt="...">
          <span class="badge-price">{{ card.badge }}</span>
          <div class="card-body ms-4">
            <div class="d-flex">
              <img class="rounded-image" :src="card.proPic" alt="">
              <h6 class="grey-title ms-3 mt-1">{{ card.name }}</h6>
            </div>
            <p class="text-start text-black fw-bold mt-2 mb-4">{{ card.text }}</p>
            <div class="d-flex justify-content-between">
              <span class="numbers-card"><i class="fa-solid fa-sheet-plastic"></i> {{ card.lessons }}</span>
              <span class="numbers-card"><i class="fa-regular fa-user"></i>{{ card.students }}</span>
            </div>
            
          </div>
        </div>
      </div>
</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";
.card {
      border: 0;
    }
  

  .badge-price {
    color: white;
    padding: 5px 10px;
    position: absolute;
    top: 0;
    right: 0;
    background-color: $brandColor;
    width: 80px;
    height: 33px;
    border-radius: 0 0.375rem 0 0;
  }
  .rounded-image {
    border-radius: 50%;
  }

  .numbers-card {
    font-size: 12px;
    color: $textSecondaryColor;
  }



</style>