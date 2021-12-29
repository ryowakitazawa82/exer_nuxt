<template>
  <section class="container">
      <p>{{ message }}</p>
      <hr>
      <router-link to="/price">Price page</router-link>
  </section>
</template>


<script>
export default {
  data: function(){
    return {
      message: 'こんにちは！'
    }
  }
}
</script>
