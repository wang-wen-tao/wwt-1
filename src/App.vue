<template>
  <div id="app">
   
    <router-view/>
  </div>
</template>

<script>
import {mapActions} from 'vuex'
export default {
  methods:{
    ...mapActions(['getdata'])
  },
  created(){
    this.getdata()
  }
}
</script>


<style lang="scss">
*{
  margin: 0;
  padding: 0;
}
html,body,#app{
  width: 100%;
  height: 100%;
}
</style>
