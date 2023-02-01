<script>
import NavbarHeader from './NavbarHeader.vue';
import JumbotronHeader from './JumbotronHeader.vue'
export default {
    name: 'AppHeader',
    components : {NavbarHeader, JumbotronHeader},
  data() {
    return {
        
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
  <header class="bg-custom">
    <NavbarHeader></NavbarHeader>
    <JumbotronHeader></JumbotronHeader>
  </header>
</template>

<style lang="scss" scoped>
header {
    min-height: 600px;

}

</style>