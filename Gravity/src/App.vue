<script>
  import NavbarGravity from './components/Navbar.vue';
  import UnderBar from './components/Footer.vue';
  import VueDetail from './components/Vue-Detail.vue';
  export default{
    name: "App",
    components:{
      NavbarGravity,
      UnderBar,
      VueDetail
    },
    data(){
      return{
        message:"App จ้า"
      }
    }
  }
</script>

<template>
  <NavbarGravity/>
  <VueDetail/>
  <UnderBar/>
</template>

<style>
  body {
    background-color: black;
    border-block-color: red;
  }
  .section {
    align-content: center;
    width: 1728px;
    height: 800px;
    justify-items: center;
    align-items: center;
  }

</style>
