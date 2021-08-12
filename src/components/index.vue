<template>
  <div class="index">
    <Header/>
    <SideBar/>
    <Footer/>
    <router-view/>
  </div>
</template>

<script>
    import Header from './Header'
    import SideBar from './SideBar'
    import MainContent from './MainContent'
    import Footer from './Footer'

    export default {
        name: 'Index',
        components:{//组件
            Header,
            SideBar,
            Footer,
            MainContent
        }

    }
</script>
<style>
  *{
    margin: 0;
    padding: 0;
  }
  body{
    background-color: #0C3563;
  }
</style>
