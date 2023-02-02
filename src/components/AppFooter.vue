<script>
export default {
  name: 'AppFooter',
  data() {
    return {
      // Your data properties 
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
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-6 py-5">
          <h3>Address</h3>
          <ul>
            <li></li>
            <li></li>
            <li></li>
          </ul>
        </div>
        <div class="col-3  py-5"></div>
        <div class="col-3  py-5"></div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";
footer {
  background-color: $bgMainColor;
  height: 400px;
}
</style>