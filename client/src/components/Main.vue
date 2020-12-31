<template>
  <div class="main">
    <h1>{{ msg }}</h1>
    <Hospital />
    <Doctor />
    <Pharmacy />
  </div>
</template>

<script>
import Hospital from "../components/Hospital";

export default {
  name: "main",
  components: {
    Hospital,
  },
  props: {
    msg: String,
  },
};
</script>
<script>
import Doctor from "../components/Doctor";

export default {
  name: "main",
  components: {
    Doctor,
  },
  props: {
    msg: String,
  },
};
</script>
<script>
import Pharmacy from "../components/Pharmacy";

export default {
  name: "main",
  components: {
    Pharmacy,
  },
  props: {
    msg: String,
  },
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
