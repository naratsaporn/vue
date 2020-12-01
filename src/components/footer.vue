<template>
  <div class="fluid-container">
    <p class="text-center">Copyright &copy {{year}}</p>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        year: new Date().getFullYear()
      };
    }
  };
</script>

<style scoped>
div{
  color: white;
  background-color: #003459;

}
</style>