<template>
  <div class="main">
    <UserPharmacy />
    <!-- <login /> -->
    <!-- <Home /> -->
  </div>
</template>

<script>
import UserPharmacy from '../components/user/user-pharmacie'
// import login from './login'
// import Home from './Home'

export default {
  name: 'main',
  components: {
    UserPharmacy,
    // login,
    // Home
  }
}
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
