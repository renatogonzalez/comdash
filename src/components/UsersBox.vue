<template lang='pug'>
  // - My wonderfull
  section#usersbox
   .navbar
      div
        ul.list
          li Index 1
          li Index 2
          li Index 3


</template>

<script>
export default {
  name: 'UsersBox'
  
}
</script>

<style scoped>
.navbar {
  background-color: #2c3e50;
  line-height: 37px;
  margin-top:-60px;
  padding: 30px
}

.title {
  color: aliceblue;
  font-size: 30px;
 
}

.list {
  text-align: right;
  list-style: none;
  color: aliceblue;
}

</style>
