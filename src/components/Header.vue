<template>
  <header>
      <a href="#">
          <!-- metto il logo -->

          <img src="@/assets/dc-logo.png" alt="dc-logo">
      </a>

      <ul>
          <li><a href="#">characters</a></li>
          <li><a href="#">comics</a></li>
          <li><a href="#">movies</a></li>
          <li><a href="#">tv</a></li>
          <li><a href="#">games</a></li>
          <li><a href="#">collectibles</a></li>
          <li><a href="#">videos</a></li>
          <li><a href="#">fans</a></li>
          <li><a href="#">news</a></li>
          <li><a href="#">shop</a></li>
      </ul>
  </header>
  
</template>

<script>
export default {
    name : 'Header'

}
</script>

<style lang="scss" scoped>
@import '../style/vars.scss';

header{
    display: flex;
    height: 100px;
    line-height: 100px;
    justify-content: space-between;
    margin-top: $margine-alto;

    img{
        margin-left:200px;
    }

    ul{
        display: flex;
        list-style: none;
         li{
            margin:0 15px;
             a{
                text-decoration: none;
                color:black;
                   &:hover{
                        background: $colore;
                          }
              }

              
           
        }
        
    }
}

</style>