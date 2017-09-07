<template>
    <div id="firstCompontents">
        <h1>This is My FirstCompontents</h1>
        <a :href="goUrl">{{msg}}</a>
    </div>
</template>
<style>
    #firstCompontents{
        background-color: #ff0;
    }
</style>

<script>
export default {
  data(){
      return {
          goUrl:'http://www.baidu.com'
      }
  }
}

</script>

