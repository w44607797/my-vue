<template>
  <div class="hello">
    <div class="left-bord">
        真没空写这个啊啊啊啊啊
    </div>
    <div class="right-bord">
    <h1>{{ msg }}</h1>

    </div>




  </div> 
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
body{
 position: absolute;
 display: flex;
}
.right-bord{
    text-align: center;
}
.left-bord{

  width: 20%;
  height: 100%;
}
</style>
