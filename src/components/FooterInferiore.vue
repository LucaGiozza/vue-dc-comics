<template>
<div class="container-footer-inferiore">

    <button>SIGN-UP NOW!</button>
    <div class="footer-right">
       <span class="follow">FOLLOW US</span>
       <img src="../assets/footer-facebook.png" alt="">
       <img src="../assets/footer-pinterest.png" alt="">
       <img src="../assets/footer-periscope.png" alt="">
       <img src="../assets/footer-twitter.png" alt="">
       <img src="../assets/footer-youtube.png" alt="">
    </div>
    

</div>
  
</template>

<script>
export default {
    name: 'FooterInferiore'

}
</script>

<style lang="scss" scoped>
.container-footer-inferiore{
    height:100px;
    background-color: rgba(0, 0, 0, 0.822);
    display:flex;
    align-items: center;
    justify-content: space-between;
    
    
    button{
        height:30%;
        
        margin-left:200px;
        width:150px;
        background-color: rgba(0, 0, 0, 0.822);
        color:white;
        border: 3px solid rgb(0, 132, 255);
        &:hover{
            cursor:pointer;
            opacity:0.6;
        }
    }
    .follow{
        color:rgb(0, 204, 255);
        padding:40px;
        font-size: 27px;
       
    }
    .footer-right{
        margin-right:30px;
        img{
            margin-left:30px;
            
        }
    }
}

</style>