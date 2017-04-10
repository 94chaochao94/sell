<template>
  <div>
    <v-header></v-header>
    <div class="tab">
     <div class="tab-item">
      <a v-link="{path: '/goods'}">商品</a>
     </div>
     <div class="tab-item">
      <a v-link="{path: '/ratings'}">评论</div>
     <div class="tab-item">
      <a v-link="{path: '/seller'}">商家</div>
    </div>
    <div class="content">
     I am content
    </div>
  </div>
</template>


<script>
import header from './components/header/header.vue'

export default {
  name: 'app',
  components: {
    Hello
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
