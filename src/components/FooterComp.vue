<template>
  <footer class="container">
    <div class="all-box-list">
      <div class="box-list-footer">
      <ul>
        <li>Characters</li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
      </ul>
      <ul>
        <li>cose</li>
        <li><a href="#">cose</a></li>
        <li><a href="#">cose</a></li>
      </ul>
    </div>
    <div class="box-list-footer">
      <ul>
        <li>Characters</li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
      </ul>
    </div>
    <div class="box-list-footer">
      <ul>
        <li>Characters</li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Characters</a></li>
      </ul>
    </div>
    </div>
    
    <img src="../assets/img/dc-logo-bg.png" alt="">

  </footer>
</template>

<script>
export default {
 name:'FooterComp',
}
</script>

<style lang="scss" scoped>
footer{
 background-image: url(../assets/img/footer-bg.jpg);
 display: flex;
 justify-content: space-between;
 .all-box-list{
   display: flex;
   .box-list-footer{
   padding: 10px 20px 50px;
   ul{
    margin-top:20px;
    li:first-child{
      color: #FFFFFF;
      font-size: 16px;
      margin-bottom: 10px;
      text-transform: uppercase;
    };
    li{
      a{
        color: #687E7B;
        font-size: 13px;
        font-weight: normal;
      };
    }; 
   };
  };
 };
 
}

</style>