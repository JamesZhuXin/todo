<template>
<div id="app">
<div id="cover"></div>
<Header></Header>
<todo></todo>
<Footer></Footer>
</div>
</template>

<script>
import Header from './todo/header.vue';
import Footer from './todo/footer.vue';
import todo from './todo/todo.vue'
export default {  
    components:{
        Header,
        Footer,
        todo,
    }
}
</script>

<style lang="stylus" scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  position: absolute;
  left: 0;
  right: 0;
  top:0;
  bottom: 0;
  z-index: -1;
}
#cover{
  position: absolute;
  left: 0;
  right: 0;
  top:0;
  bottom: 0;
  background-color: #999999ab;
  opacity: 0.9;
  z-index: -1;
}
</style>

