<template>
  <div id="app">
    <main id="main-container">
     <NaviDesktop/>
      <main>
        <router-view/>
      </main>
    </main>
  </div>
</template>

<style lang="scss">
  @import 'styles/styles';
</style>
<script>
import NaviDesktop from './components/navigation/NaviDesktop'
export default {
  components: { NaviDesktop }
}
</script>
