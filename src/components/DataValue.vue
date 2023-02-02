<script>
export default {
  name: 'DataValue',
  data() {
    return {
      
    };
  },
  props: {
  number: Object
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
            <h2 class="text-center">{{ number.title }}</h2>
            <h6 class="text-center">{{ number.text }}</h6>
          </div>
</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";

 h2 {
    font-weight: bold;
    color: $brandColor;
  }
</style>