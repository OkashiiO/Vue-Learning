<template>
    <div>
      <p class="msg">{{msg}}</p>
    </div>
</template>

<script>
  export default {
    data () {
      return {
        msg: 'Hello Vue'
      }
    },
  }
</script>

<style>
 .msg{
   color:red;
 }
</style>
