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
  color: #20AD96;
  margin: 0 10px;
}
.grey-title {
  color: #696969;
}
</style>