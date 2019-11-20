<template lang='pug'>
  section#pickbox
    div.overview 
      h1.overview-txt Overview
    div.column1
      p.column1-txt 
        | The general rendering process of Pug is simple. pug.compile() will compile the Pug source code into a 
        |JavaScript function that takes a data object (called &ldquo;locals&rdquo;) as an argument. Call that resultant function with your data, 
        |and voil&agrave;!, it will return a string of HTML rendered with your data.
        | The compiled function can be re-used, and called with different sets of data.

</template>
<script>
export default {
  name: 'PickBox'
}
</script>

<style scoped>
.overview {
  margin-top: 50px;
  margin-left: 300px;
}

.overview-txt {
  text-align: left;
  font-size: 40px
}

.column1 {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px;
  margin-left: 20%;
  line-height: 37px;
}

.column1-txt {
  text-align:left;
  font-size: 20px
  
}
</style>
