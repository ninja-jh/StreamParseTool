<template>
  <MainNavPage/>
  <div class="main_widget">
    <!-- <div class="main_top_menu_bar">
      <TopMeunBar/>
    </div>

    <div class="main_bottom_nav">

    </div> -->
  </div>
</template>

<script>
// import TopMeunBar from '@/components/TopMeunBar.vue';
import MainNavPage from '@/components/MainNavPage.vue';

export default {
  name: 'App',
  components: {
    MainNavPage
  }
}
</script>

<style>
#app {
  font-family: 'Microsoft YaHei', sans-serif;
}

.main_widget{
  margin: 0;
  padding: 0;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  border: 1px solid #333333;
  /* background-color: aquamarine; */
}


</style>
