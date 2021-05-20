<template>
  <section class="container">
    <ul>
      <li>
        <a href="#">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <h4>DIGITAL COMICS</h4>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
          <h4>DIGITAL COMICS</h4>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <h4>DIGITAL COMICS</h4>
        </a>
      </li>
      <li>
        <a href="#">
          <img class="special-img-shop" src="../assets/img/buy-comics-shop-locator.png" alt="">
          <h4>DIGITAL COMICS</h4>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
          <h4>DIGITAL COMICS</h4>
        </a>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
 name:'SectionShopComp',
}
</script>

<style lang="scss" scoped>
@import '../assets/style/vars.scss';
section{
  background-color: $color-blue;
  height: 150px;
  display: flex;
  align-items: center;
  ul{
    display: flex;
    justify-content: space-evenly;
    width: 100%;
    li{
      display: flex;
      align-items: center;
      a{
        display: flex;
        align-items: center;
        img{
          width: 40px
        };
        img.special-img-shop{
          width: 30px
        };
        h4{
          font-size: 12px;
          color: #FFFFFF;
          margin-left: 10px;
        };
      };
      a:hover h4{
        color: #000000;
      };


    };
  };
}
</style>