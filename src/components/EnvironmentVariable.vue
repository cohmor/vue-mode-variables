<template>
  <div class="environment-variable">
    <h1>{{ environment_variable }}</h1>
  </div>
</template>

<script>
export default {
  name: "EnvironmentVariable",
  data: function() {
    return { 
      environment_variable: "" 
    };
  },
  created() {
    this.environment_variable = process.env.VUE_APP_API_URL;
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
