<template>
<div class="jumbo">
     <img src="../assets/jumbotron.jpg" alt="">
     <button class="bottone-jumbo">current series</button>

</div>
  
</template>

<script>
export default {
    name : 'Jumbotrone'

}
</script>

<style lang="scss" scoped>
.jumbo{
    height:500px;
    margin-top:15px;
    img{
        max-height: 100%;
         width:100%;
         


    }
    .bottone-jumbo{
       padding: 10px 30px;
       
       margin-top: -20%;
       margin-left: 192px;
       text-transform: uppercase;
       color:white;
       background-color: rgb(0, 119, 255);
       border:none;
       &:hover{
           opacity:0.5;
           cursor:pointer
       }
    }
}



</style>