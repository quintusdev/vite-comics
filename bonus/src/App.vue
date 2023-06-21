<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppIcon from './components/AppIcon.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppIcon,
    AppFooter    
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppIcon />
  <AppFooter /> 
</template>

<style lang="scss">
  @use './styles/generals.scss' as *;
</style>
