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
        <div class="col-5 py-5">
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
        <div class="col-4  py-5">
          <h5>Explore</h5>
          <div class="d-flex">
            <ul>
              <li><a href="#">Start here</a></li>
              <li><a href="#">Blog</a></li>
              <li><a href="#">About us</a></li>

          </ul>
          <ul class="right-list-column">
            <li><a href="#">Success story</a></li>
            <li><a href="#">Courses</a></li>
            <li><a href="#">Contact us</a></li>
          </ul>
          </div>
          
          
        </div>
        <div class="col-3  py-5">
          <h5>Information</h5>
          <ul>
            <li><a href="#">Membership</a></li>
            <li><a href="#">Purchase guide</a></li>
            <li><a href="#">Privacy policy</a></li>
            <li><a href="#">Terms of services</a></li>
          </ul>  

        </div>
      </div>
    <section id="credits" class="text-center">
      <p>© 2020 MaxCoach, All Rights Reserved</p>
    </section>

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

    a {
    margin-bottom: 12px;
    color: $textSecondaryColor;
    font-size: 12px;
    }

    .fa-brands {
    color: $textSecondaryColor;
    margin-right: 20px;
    font-size: 25px;
    }
  }

  .right-list-column {
    margin-left: 50px;
  }

  #credits {
    p {
      font-size: 10px;
      color: $textSecondaryColor;
      font-weight: bold;
    }
  }
}
</style>