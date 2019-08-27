<template>
  <div id="app">
      <section class="container">
        <nav id="nav">
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About</router-link>
        </nav>
        <main>
          <router-view/>
        </main>
      </section>
    <footer>
    </footer>
  </div>
</template>

<style lang="scss">
  @import 'styles/styles';
</style>
