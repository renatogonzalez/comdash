<template lang='pug'>
  section#infobox
    h1 Título
    p Este es un parrafo feo
    h3 Este es el tercer parrafo
    button(style="border-radius:10px; border:3px solid red; background:yellow; width:200px; height:100px;")
      a(href='google.com' style="font-size:30px; display:block") Click aquí

    div(style="position:fixed; left:20px; top:300px; border:3px solid blue")
      iframe(width='460', height='220', src='https://www.youtube.com/embed/UyNufyV3VCo', frameborder='0', allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture', allowfullscreen='')

      
</template>

<script>
export default {
  name: 'InfoBox'
}
</script>

<style scoped>
</style>