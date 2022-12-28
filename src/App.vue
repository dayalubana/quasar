<template>
  <div class="root">
    <div class="sidebar">
      <Sidebar/>
    </div>
    <div class="right-panel">
      <div class="header">
        <Header/>
      </div>
      <div class="content">
        <AppContent/>
      </div>
    </div>
  </div>
</template>
<script>
// import { ref } from 'vue'
import Header from './components/AppHeader.vue'
import Sidebar from './components/AppSidebar.vue'
import AppContent from './components/AppContent.vue'

export default {
  name: 'LayoutDefault',

  components: {
    AppContent,Header,Sidebar
  },
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Inter');
.root{
  display: flex;
  height: 100vh;
}
.sidebar{
    width: 300px;
    background: #0C2508;
    border-radius: 16px;
}
.right-panel{
  width: 100%;
  overflow-y: auto;
}
</style>