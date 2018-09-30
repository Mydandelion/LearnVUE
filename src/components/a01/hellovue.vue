<template>
    <div id="vue">Hello Vue! {{message}}</div>
</template>

<script>
export default {
  name: 'hellovue',
  data () {
    return {
      message: 'YOU MUST BE SUCESS!'
    }
  }
}
</script>

<style type="text/css">
  #vue{
    color:blueviolet;
    font-size:28px;
  }

</style>
