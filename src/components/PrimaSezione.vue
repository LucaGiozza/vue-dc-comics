<template>

<div class="container-first">
    <div class="foto-container">
        <Carte class="foto" v-for="(product,index) in PrimaSezione" :key="index" :prod="product" />


    </div>
    
    

</div>

  
</template>

<script>
import Carte from '@/components/Carte.vue'
import Film from '@/copertine/Film.js';
export default {
   name:'PrimaSezione',
   components : {
       Carte

   },
   data(){
       return {
           PrimaSezione: Film
       }
   }

}

</script>



<style lang="scss" scoped>

.container-first{
    background-color: black;
     
     width:100%;
     display:flex;
     .foto-container{
        //  height:100%;
        width:80%;
         display:flex;
         flex-wrap: wrap;
         margin:auto;

         justify-content: center;
          .foto{
              
            
        //  height:100px;
         padding:50px 50px;
         
        
       
       
       
           
            
        
        
              
    }
   


     }
     
         
   
   

    

     
         
}


</style>