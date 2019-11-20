<template lang='pug'>
  section#infobox
    div.title
      h1.get.start Getting Started
    div.installation
      h2.install-txt Installation
    div.instruction
      h3.instruction-txt pug is availale in npm:
    div.install-box 
      p.text-code $ npm install pug
</template>

<script>
export default {
  name: 'InfoBox'
}
</script>

<style scoped>
.title {
  margin-left: 225px;
}

.get.start {
  font-size: 40px;
  text-align: left
}

.installation {
  margin-left: 230px;
}

.install-txt {
  text-align: left;
  font-size: 30px;
}

.instruction {
  margin-left: 400px;
}

.instruction-txt {
  text-align: left;
}

.install-box {
  border: 2px solid #2c3e50;
  margin-left: 400px;
  margin-right: 800px
}

.text-code {
  font-size: 20px;
}
</style>