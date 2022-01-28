<template>
  <div>
    <nav class=" blend">
        <!-- <span class="logo">Dee - Why</span> -->
        <div class="w-100 d-flex">
            <ul class="ml-auto" style="display: block;" >
                <li class="nav-link" v-on:click="toggleNav">
                    <span>Menu</span>
                </li>
                <!-- <li class="nav-link">
                    <a href="">About</a>
                </li>
                <li class="nav-link">
                    <a href="">Contact</a>
                </li> -->
            </ul>
        </div>
        <div class="navbar-toggler ml-auto" type="button" id="navbartoggler" style="display: none;">
            <span class="h-bar-1"></span>
            <span class="h-bar-2"></span>
            <span class="h-bar-3"></span>
        </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
      isActive: true
    }
  },
  methods: {
    toggleNav () {
      this.isActive = !this.isActive
    }
  }
}
</script>
