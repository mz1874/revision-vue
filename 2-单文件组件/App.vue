<template>
  <div>
      <School></School>
      <Student></Student>
  </div>
</template>


<script>

import Student from "./Student";
import School from "./School";
export default({
    name:'App',
    data(){
    },

    methods:{

    },
    components:{
        School,
        Student
    }
})
</script>


<style>
.demo{
    background-color: red;
}
</style>