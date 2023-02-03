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
          <h5>Address</h5>
          <ul>
            <li>382 NE 191st St # 87394, Miami, FL 33179-3899</li>
            <li>+1(305)547-9909 (9am - 5pm EST, Monday - Friday)</li>
            <li>support@maxcoach.com</li>
            <li><a href="#"><i class="fa-brands fa-square-facebook"></i></a>
              <a href="#"><i class="fa-brands fa-twitter"></i></a>
              <a href="#"><i class="fa-brands fa-instagram"></i></a>
              <a href="#"><i class="fa-brands fa-linkedin"></i></a>
            </li>
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
  
  h5{
    color: $textSecondaryColor;
    font-weight: bold;
    margin-bottom: 18px;
    margin-top: 25px;

  }

  ul {
    padding: 0;
  }

  li {
    margin-bottom: 12px;
    color: $textSecondaryColor;
    font-size: 12px;

    .fa-brands {
    color: $textSecondaryColor;
    margin-right: 20px;
    font-size: 25px;
    }
  }
}
</style>