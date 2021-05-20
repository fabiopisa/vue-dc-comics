<template>
  <footer>
    <section class="footer-link container">
      <div class="all-box-list">
      <div class="box-list-footer">
      <ul>
        <li>dc comics</li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">News</a></li>
      </ul>
      <ul>
        <li>shop</li>
        <li><a href="#">Shop DC</a></li>
        <li><a href="#">Shop DC Collectibles</a></li>
      </ul>
    </div>
    <div class="box-list-footer">
      <ul>
        <li>dc</li>
        <li><a href="#">Terms Of Use</a></li>
        <li><a href="#">Privacy policy (New)</a></li>
        <li><a href="#">Ad Choices</a></li>
        <li><a href="#">Advertising</a></li>
        <li><a href="#">Jobs</a></li>
        <li><a href="#">Subscriptions</a></li>
        <li><a href="#">Talent Workshops</a></li>
        <li><a href="#">CPSC Certificates</a></li>
        <li><a href="#">Ratings</a></li>
        <li><a href="#">Shop Help</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </div>
    <div class="box-list-footer">
      <ul>
        <li>sites</li>
        <li><a href="#">DC</a></li>
        <li><a href="#">MAD Magazine</a></li>
        <li><a href="#">DC Kids</a></li>
        <li><a href="#">DC Universe</a></li>
        <li><a href="#">DC Power Visa</a></li>
      </ul>
    </div>
    </div>
    
    <div class="img-logo-bg">
      <img src="../assets/img/dc-logo-bg.png" alt="">
    </div>
    </section>
    <section class="footer-follow container">
      <div class="link-sing-up">
        <a href="#">sign-up now!</a>
      </div>

      <div class="box-follow-us">
        <ul>
          <li><a href="#">follow us</a></li>
          <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
        </ul>
      </div>
    </section>
    

  </footer>
</template>

<script>
export default {
 name:'FooterComp',
}
</script>

<style lang="scss" scoped>
@import '../assets/style/vars.scss';
footer{
 background-image: url(../assets/img/footer-bg.jpg);
 background-repeat: no-repeat;
 background-size: cover;
 .footer-link{
   display: flex;
   justify-content: space-between;
   .all-box-list{
    display: flex;
    .box-list-footer{
      padding: 10px 10px 50px;
      ul{
        margin-top:20px;
        li:first-child{
          color: #FFFFFF;
          font-size: 15px;
          margin-bottom: 10px;
          text-transform: uppercase;
        };
        li{
            a{
              color: #687E7B;
              font-size: 12px;
              font-weight: normal;
            };
            a:hover{
              color:$color-blue;
                
            };
          }; 
      };
    };
   };
   .img-logo-bg{
      height: 358px;
      overflow: hidden;
      text-align: right;
      img{
        margin-top: -70px;
        width: 85%
      };
    };
 };
 
 .footer-follow{
   background-color: #303030;
   height: 80px;
   display: flex;
   justify-content: space-between;
   align-items: center;
   .link-sing-up{
     a{
       color:#FFFFFF;
       text-transform: uppercase;
       border: 1px solid $color-blue;
       font-size: 15px;
       padding: 10px
     };
     a:hover{
       color: $color-blue;
       background-color: #FFFFFF
     };
   };
   .box-follow-us{
     ul{
       display: flex;
       align-items: center;
       li{
         text-transform: uppercase;
         a{
           color:$color-blue;
           margin: 0 10px;
           font-size: 17px;
           display: flex;
           align-items: center;
           img{
             width: 25px;
             border-radius: 50%;
           }
           img:hover{
             box-shadow: 1px 1px 5px #FFFFFF
           };
         };
         a:hover{
           color: #FFFFFF;
         };
       };
     };
   };
 };
 
}

</style>