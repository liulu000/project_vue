<template>
  	<div class="header">
   		<div class="header_l">
            <a>菜单栏</a>
            <p>技术支持微测试</p>
        </div>
        <div class="header_r">
            <a class="ico_01" href="fnews.php?id=110&amp;act=creat&amp;uid=1"> 购物车 </a>
        </div>
  	</div>
</template>

<script>
export default {
  name: 'hello',
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
