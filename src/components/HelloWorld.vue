<template>

  <div class="helloworld">

  <div class="pic">

    <img src="../assets/001.jpg" width="100%"/>

    <div class="box"><img src="../assets/002.jpg" width="100%"/></div>

  </div>

  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
  .pic{

    position: absolute;
    width: 1010px;
    height: 1534px;
    top: 0;
    left: 50%;
    margin-left: -505px;


  }

  .box{

    position: absolute;
    width: 633px;
    height: 355px;
    top: 844px;
    left: 50%;
    margin-left: -318px;

  }
</style>
