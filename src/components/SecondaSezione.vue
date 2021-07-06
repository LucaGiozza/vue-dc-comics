<template>
<div class="container-second">
    <div class="foto-text">
        <a href="#">
        <img src="@/assets/first.png" alt="dc-logo">
        <span>Digital Comics</span>
        <img src="@/assets/second.png" alt="dc-logo">
        <span>DC Merchandise</span>
        <img src="@/assets/third.png" alt="dc-logo">
        <span>Subscription</span>
        <img src="@/assets/fourth.png" alt="dc-logo">
        <span>Comic Shop Locator</span>
        <img src="@/assets/cinque.svg" alt="dc-logo">
        <span>Dc Power Visa</span>
      </a>

    </div>
    

</div>
  
</template>

<script>
export default {
    name: 'SecondaSezione'

}
</script>

<style lang="scss" scoped>
.container-second{
    height:150px;
    background-color: rgb(0, 38, 255);
    width:100%;
    padding:30px 10px;
    
    .foto-text{
        
        text-align: center;
       
        
        
        img{
            margin-left:80px;
            height: 90px;
            vertical-align:middle;
           }
           span{
                margin-left:10px;

           }
           a{
               text-decoration: none;
               color:white;
               
           }
    }
}

</style>