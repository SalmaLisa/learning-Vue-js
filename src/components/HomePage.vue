<template>
<h1>Don't be afraid, Salma. Your prime guardian is always here for you. keep faith on Him and follow the route He guides.</h1>
<p v-if="show">Show</p>
<p v-else>Hide</p>
<button @click="show=!show">toggle</button>
<ChildComp></ChildComp>
</template>

<script>
import ChildComp from './ChildComp.vue';
export default {
  name: 'HomePage',
  data() {
    return {
      tech:["react","vue","angular"]
    }
    
  },
      methods: {
        getData() {
          console.log()
     }
  },
  components: {
      ChildComp
    }
}
</script>
<style scoped>
h1{
  font-size: 50px;
  color: blue;
}
</style>