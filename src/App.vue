<template>
  <Header/>
  <Body/>
  <Footer/>
</template>

<script>
import Header from './components/PageHeader';
import Body from './components/PageBody';
import Footer from './components/PageFooter';

export default{
  name:'App',
  components:{
    Header,
    Body,
    Footer
  }
  
}
</script>

<style>

</style>
