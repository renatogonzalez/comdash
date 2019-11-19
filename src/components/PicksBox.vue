<template lang='pug'>
  section#pickbox
    div(style='border: 2px solid red; padding:10%; background-color:#e68ac0')
      ul(style="list-style:none")
        li
          a(href='www.google.cl' title="Página Kulia" style="background-color:red; color:white; font-size:40px") Google
        li
          a(href='www.google.cl' title="Segundo parrafo") Google 2
        li 
          a(href='www.google.cl' title='tercer parrafo culiao') Google 3

    img(src='/Users/renato/dev/buttontest/Images/header.jpg' alt='Foto' style='width:100%;')




</template>
<script>
export default {
  name: 'PickBox'
}
</script>

<style scoped>
</style>
