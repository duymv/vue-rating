<template>
  <div class="hello">
    <h1>{{ vue_rating }}</h1>
    <span>{{ username }} </span>
    <input type="text" placeholder="Enter your review">
    <button id="submit_btn">Submit your review</button>
  </div>
</template>

<script>
export default {
  name: "RatingController",
  props: {
    msg: String,
    vue_rating: String,
    username: String
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
