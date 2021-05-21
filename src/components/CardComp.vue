<template>
 
  <div>
    <img :src="card.thumb" alt="">
    <h4>{{card.series}}</h4>
  </div>
  
</template>

<script>
export default {
 name:'CardComp',
 props:{
   cardSingle:Object
 }
}
</script>

<style lang ="scss" scoped>
img{
  width: 80%;
  height:20vh;
  margin: 0 10%;      
};
h4{
  color: #FFFFFF;
  font-size: 10px;
  text-transform: uppercase;
  margin-top: 15px;
  padding: 0 15px
};
</style>