<template>
  <main class="container">
    <ul>
      <li
      v-for="(card, index) in cards"
      :key="index"
      >
        <CardComp
        :card="card"
        />
        <!-- <img :src="card.thumb" alt="">
        <h4>{{card.series}}</h4> -->
      </li>
    </ul>

    <button>LOAD MORE</button>
  </main>
</template>

<script>
import cards from '../assets/data/dc-comics.js';
import cardSingle from 'CardComp';

export default {
 name:'MainComp',
 data(){
   return {cards, cardSingle}
 },
 mounted(){
   console.log(cards);
 }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/mixin.scss';
main{
  background-color: #1C1C1C;
  text-align: center;
  ul{
    padding: 50px 0 30px;
    display: flex;
    text-align: center;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    li{
      flex-basis: calc(100% / 6);
      margin-bottom: 30px;
      text-align: left;
      height: 25vh;
      /* img{
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
      }; */

    };
  };
  button{
    @include button-blue;
    margin-bottom: 20px;
    font-size: 10px;
    padding: 5px 30px;
  };
}
</style>