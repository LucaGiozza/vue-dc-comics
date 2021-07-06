<template>
<div class="contenitore-footer-superiore">

    <ul>
        <li class="li-title">DC COMICS</li>
        <li>Comics</li>
        <li>Tv</li>
        <li>Movies</li>
        <li>Games</li>
        <li>Films</li>
        <li>News</li>
        <li>Charatcters</li>
        <li class="li-title">SHOP</li>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
    </ul>
    <ul>
        <li class="li-title">DC </li>
        <li>Term of Use</li>
        <li>Privacy</li>
        <li>Ad Choises</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent</li>
        <li>CPSC</li>
        <li >Ratings</li>
        <li> Shop Help</li>
        <li>Contact Us  </li>
        <li></li>
    </ul>
    <ul>
        <li class="li-title">SITES </li>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids </li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
        
    </ul>
    <img src="../assets/dc-logo-bg.png" alt="">


</div>
  
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.contenitore-footer-superiore{
    height: 350px;
    width:100%;

    background-image: url("../assets/footer-bg.jpg");

    img{
        float:right;
        height:100%;
        margin-right:50px;

    }
    ul{
        display:inline-block;
        list-style: none;
    }
    li{
        color:grey;
        padding:0 30px;
        cursor:pointer;
        &:hover{
            color:white;
            text-decoration:underline;
        }
    }
    .li-title{
        color:white;
        font-size: 20px;
        padding : 10px 30px;
        padding-top:20px;
    }

}

</style>