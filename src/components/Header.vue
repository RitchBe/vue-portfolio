<template>
  <div id="background">

  </div>

</template>



<script>
export default{
  name: 'Header',
  data: function() {
    return {
      message: "mofo"
    }
  }
}
</script>
<style scoped>

#background {
    background-image: url('../../images/bg.png');
    background-size: cover;
    width: 100%;
    height: 100vh;
    z-index: 1;
    filter: blur(3px);
    position: absolute;
    top:0;
    left: 0;
    z-index: 0;
}



</style>