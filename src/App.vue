<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
export default {
    components : {AppHeader, AppMain, AppFooter},
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
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
@import "./assets/styles/variables.scss";

//UTILITIES GENERALI

* {
    color: #3F3A64;
}
a {
    text-decoration: none;
    color: black;
}
li {
    list-style-type: none;
}
.highlighted {
  color: $brandColor;
  margin: 0 10px;
  font-weight: 1;
}
.grey-title {
  color: $textSecondaryColor;
}

.rounded-image {
    border-radius: 50%;
  }

  .btn-green{
    background-color: $brandColor;
    color: white;
  }

  .btn-green:hover {
    background-color: $textPrimaryColor;
    color: white;
  }
</style>