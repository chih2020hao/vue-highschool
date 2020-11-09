<template lang="pug">
  #app
    Top
    #left
      Menu
      update
    #right
      mar
      Main
    Footer
</template>

<script>
import Top from './components/Top'
import Menu from './components/Menu'
import update from './components/Update'
import mar from './components/Mar'
import Main from './components/Main'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Top,
    Menu,
    update,
    mar,
    Main,
    Footer
  }
}
</script>
