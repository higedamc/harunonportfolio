<template>
    <div id="home">
    <card/>
    <skill/>
    <sns/>
    <contact/>
  </div>
</template>

<script>
import card from '../components/card.vue'
import contact from '../components/contact.vue'
export default {
  name: 'home',
  components: {
    card,
    contact
  }
}
</script>

<style scoped>
#home {
  font-family: Meiryo, "Hiragino Kaku Gothic Pro W3", Courier New, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top: 60px;
}
html{
  width: 80%;
  margin: 10px auto;
  background: linear-gradient(to right, #fbc2eb 0%, #a6c1ee 51%, #fbc2eb 100%);

}
ui.header{
  color: #fff;
}
body{
  background: 0%;
}

</style>
