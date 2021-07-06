<template>
  <div id="app">
    
       <Header/>

        <main>
          <PrimaSezione/>
          <SecondaSezione/>
       </main> 

       <!-- <Footer/> -->
        
  </div>
</template>

<script>
 import Header from './components/Header.vue';
  import PrimaSezione from './components/PrimaSezione.vue';
   import SecondaSezione from './components/SecondaSezione.vue';
//  import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
     Header,
      PrimaSezione,
      SecondaSezione,
    //  Footer
  }
}
</script>

<style lang="scss">
@import 'style/commons.scss';


</style> 
