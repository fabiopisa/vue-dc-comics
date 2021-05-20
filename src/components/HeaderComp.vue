<template>
  <header>
    <a href="#">
      <img src="../assets/img/dc-logo.png" alt="">
    </a>
    <ul>
      <li><a href=""></a></li>
    </ul>
    <div class="box-list"></div>
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
          current: true
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
</script>

<style lang="scss" scoped>
header{
  background-color: grey;
  height: 100px;
  padding: 0 20%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  a{
    img{
      width: 75px;
    }
  }

}
</style>