<template>
  <div id="nav">
    <Navbar/>
  </div>
  <Sidebar/>
  <router-view/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Sidebar from './components/Sidebar.vue'
export default {
  components: {
    Navbar,
    Sidebar
  }
}
</script>
