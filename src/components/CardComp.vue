<template>
 
  <li>
    <img :src="cardSingle.thumb" :alt="cardSingle.type">
    <h4>{{cardSingle.series}}</h4>
  </li>
  
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
li{
  flex-basis: calc(100% / 6);
  margin-bottom: 30px;
  text-align: left;
  height: 25vh;
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
    padding: 0 15px;
  };

};
</style>