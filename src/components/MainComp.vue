<template>
  <main class="container">
    <ul>
        <CardComp
        v-for="(card, index) in cards"
        :key="index"
        :cardSingle="card"
        />
    </ul>

    <button>LOAD MORE</button>
  </main>
</template>

<script>
import cards from '../assets/data/dc-comics.js';
import CardComp from '@/components/CardComp.vue';

export default {
 name:'MainComp',
 components:{
    CardComp
 },
 data(){
   return {cards, CardComp}
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
  };
  button{
    @include button-blue;
    margin-bottom: 20px;
    font-size: 10px;
    padding: 5px 30px;
  };
}
</style>