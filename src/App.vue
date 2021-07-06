<template>
  <div id="app">
    
       <Header/>

        <main>
          <PrimaSezione/>
          <SecondaSezione/>
       </main> 

       <footer>
          <Footer/>
          <FooterInferiore/>

       </footer>

       
        
  </div>
</template>

<script>
  import Header from './components/Header.vue';
  import PrimaSezione from './components/PrimaSezione.vue';
  import SecondaSezione from './components/SecondaSezione.vue';
  import Footer from './components/Footer.vue';
  import FooterInferiore from './components/FooterInferiore.vue';

export default {
  name: 'App',
  components: {
     Header,
      PrimaSezione,
      SecondaSezione,
      Footer,
      FooterInferiore
  }
}
</script>

<style lang="scss">
@import 'style/commons.scss';


</style> 
