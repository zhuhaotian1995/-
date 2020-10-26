<template>
<div>
  <header class="site-header jumbotron">
    <div class="container">
      <div class="row">
        <div class="col-xs-12">
          <h1>我是iphone12</h1>
        </div>
      </div>
    </div>
  </header>
  <div class="container">
    <Add></Add>
    <List></List>
  </div>

</div>
</template>

<script>
import List from './components/List'
import Add from './components/Add'

export default {
  name: 'App',
  components: {
    List,
    Add
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
