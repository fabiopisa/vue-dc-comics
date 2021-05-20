<template>
  <header class="container">
    <a href="#">
      <img src="../assets/img/dc-logo.png" alt="">
    </a>
    <div class="box-list">
      <ul>
      <li v-for="(link, index) in links" :key="index + 'header list'">
        <a href="link.url" :class="{'active': link.current}">{{link.text}}</a>
      </li>
    </ul>
    </div>
  </header>
</template>

<script>
export default {
 name:'HeaderComp',
 data(){
   return{
      links:[
        {
          text:'CHARACTERS',
          url: '#',
          current: false
        },
        {
          text:'COMICS',
          url: '#',
          current: false
        },
        {
          text:'MOVIES',
          url: '#',
          current: false
        },
        {
          text:'TV',
          url: '#',
          current: false
        },
        {
          text:'GAMES',
          url: '#',
          current: false
        },
        {
          text:'COLLECTIBLES',
          url: '#',
          current: false
        },
        {
          text:'VIDEOS',
          url: '#',
          current: false
        },
        {
          text:'FANS',
          url: '#',
          current: false
        },
        {
          text:'NEWS',
          url: '#',
          current: false
        },
        {
          text:'SHOP',
          url: '#',
          current: false
        }
      ]
   }
 }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/vars.scss';
header{
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  a{
    padding: 36px 10px;
    font-size: 12px;
    color: #000000;
    &:hover,
    &.active{
      color:$color-blue ;
      border-bottom: 3px solid $color-blue ;
    }
    img{
      width: 75px;
    };
  };
  ul{
    display: flex;
  };

}
</style>