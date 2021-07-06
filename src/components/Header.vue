<template>
  <header>
      <a href="#">
          <!-- metto il logo -->

          <img src="@/assets/dc-logo.png" alt="dc-logo">
      </a>

      <ul>
          <li v-for="(link,index) in titoli" :key="index" :class="link.current ? 'active' : '' "><a :href="link.url" >{{link.text}}</a></li>
         
      </ul>
  </header>
  
</template>

<script>
export default {
    name : 'Header',
    data(){
        return{
            titoli:[
               {
                   text: 'characters',
                   url : '#',
                   current : false
               },
                {
                   text: 'comics',
                   url : '#',
                   current : true
               },
                {
                   text: 'movies',
                   url : '#',
                   current : false
               },
                {
                   text: 'tv',
                   url : '#',
                   current : false
               },
                {
                   text: 'games',
                   url : '#',
                   current : false
               },
                {
                   text: 'collectibles',
                   url : '#',
                   current : false
               },
                {
                   text: 'videos',
                   url : '#',
                   current : false
               },
                {
                   text: 'fans',
                   url : '#',
                   current : false
               },
                {
                   text: 'news',
                   url : '#',
                   current : false
               },
                {
                   text: 'shop',
                   url : '#',
                   current : false
               }

            ]
        }
    }

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
                   &.active {
                        background-color: red;
                        
                    }
              }

              
           
        }
        
    }
}

</style>