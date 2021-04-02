<template>
  <div id="app">
    <header>
      <h1>{{ msg }}</h1>
    </header>
    <main>
      <aside class="sidebar">
        <div>
          The sidebar
        </div>
      </aside>  
      <div class="content">
        Primary content. Blagh d blagh.
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Thrashing Code 100 Days of Chaotic Programming!'
    }
  }
}
</script>

<style>
</style>
