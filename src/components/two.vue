<template>
  	<div class="header">
   		我是第二个
  	</div>
</template>

<script>
export default {
  name: 'two',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .header{
        width: 100%;
        height: 42px;
        background: #fd0a48;
    }
    .header_l{
        float: left;
    }
    .header_r{
        float: right;
    }
</style>
