<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
   
  </div>
  <button @click="goToDaybook" class="btn btn-primary" >DAYBOOK </button>
</template>

<script>
export default {
  methods:{
    goToDaybook(){
      this.$router.push({name:'no-entry'})
    }
  }
}

</script>


