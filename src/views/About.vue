<template>
  <div class="about">
    <h1>{{page}}</h1>
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
    // class Anmai {
    //   name: string,
    //   constructor(parameters) {
    //     console.log(parameters)
    //   }
    // }
export default Vue.extend({
  data(){
    return{
      page: '😁'
    }
  },
  mounted(){
    // this.test()
console.log(this.page)
  },
  methods:{
    test(){
      const name = `fuxiang`
      this.page = `my name is ${name}`
      const array: unknown[] =[1,'2',3]
      array.forEach(vl =>{
        console.log(vl)
      })
      enum color { red='red', blue= 'blue' }
      const colors: color = color.red
      console.log(colors)
      let nosure: unknown = 4
      nosure = 'fuxioang'
      console.log(nosure);

    }
  }
})
</script>
