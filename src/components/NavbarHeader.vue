<script>
export default {
    name: 'NavbarHeader',
  data() {
    return {
        links: [
                {
                    text: 'Home',
                    href: '#'
                },
                {
                    text: 'Pages',
                    href: '#'
                },
                {
                    text: 'Courses',
                    href: '#'
                },
                {
                    text: 'Features',
                    href: '#'
                },
                {
                    text: 'Blog',
                    href: '#'
                },
                {
                    text: 'Shop',
                    href: '#'
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
  <nav>
    <div class="container d-flex justify-content-between">
        <!-- LOGO -->
        <figure>
                <a href="#"><img src="../assets/img/dark-logo.png" alt=""></a>
        </figure>

        <!-- MENU NAVBAR -->
        <ul class="d-flex justify-content-between">
        
            <li v-for="link in links"><a href="#">{{ link.text }} <i class="fa-solid fa-caret-down"></i></a></li>
            <li><i class="fa-solid fa-cart-shopping"></i></li>
            <li><i class="fa-regular fa-user"></i></li>
            <li>
                <!-- SEARCHBAR -->
                <input class="form-control me-2" type="search" placeholder="Search " aria-label="Search ">               
            </li>
            
        </ul>
       
       
    </div>
  </nav>
</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";

* {
    color: #3F3A64;
}
nav {
    background-color: $bgBeige;
    height: 100px;
    padding-top: 35px;

    div {
        figure {
            margin-left: 70px;
            img{
                height: 25px;
            }
    }
    }
    li {
        margin-right: 30px;

        .form-control {
            bottom: 7px;
            position: relative;
        }
    }
}
</style>