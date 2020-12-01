<template>
  <div id="app">
    <app-header></app-header>
    <div style="min-height:750px;">

      <router-view></router-view>

    </div>
    <app-footer></app-footer>
  </div>
</template>

<script>

import top from './components/top'
import footer from './components/footer'

export default {
    name: 'App',
    components: {
      'app-header': top,
      'app-footer' : footer
    },
    methods: {
      Profile () {
        this.$router.push({ path: '/profile' })
      },
      Exam () {
        this.$router.push({ path: '/exam' })
      }

    }
    
  }


</script>

<style>
 
</style>