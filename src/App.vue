<template>
  <div id="app">
    <div class="mdl-layout mdl-js-layout mdl-layout--fixed-drawer">
      <div class="mdl-layout__drawer">
        <span class="mdl-layout-title">Your Organization</span>
        <nav class="mdl-navigation">
        </nav>
      </div>
        <main class="mdl-layout__content">
          <!-- route outlet -->
        </main>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: 'Hello Vue!'
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
