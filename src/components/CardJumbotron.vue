<script>
export default {
  name: 'CardJumbotron',
  data() {
  return {};
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
  <div>
      <div>
        <h1>{{ card.title }}</h1>
        <p>{{ card.text }}</p>
        <a href="#" v-html="card.button" class="btn btn-green"></a>
      </div>
    </div>
</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";

div {
    div {
        margin-left: 32px;
        margin-top: 100px;
    }
}

</style>