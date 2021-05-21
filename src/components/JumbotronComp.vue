<template>
  <section>
    <div class="jumbotron">
      <button>CURRENT SERIES</button>
    </div>
  </section>
</template>

<script>
export default {
 name:'JumbotronComp'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/mixin.scss';
.jumbotron{
  height:40vh;
  background-image: url(../assets/img/jumbotron.jpg);
  background-size: cover;
  position: relative;
  button{
    @include button-blue; 
    font-size: 20px;
    position: absolute;
    left: 15%;
    bottom: -3vh;
  };
}
</style>