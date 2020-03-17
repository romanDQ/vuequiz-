<template>
    <div>
      <b-nav tabs>
        <b-nav-item disabled><b>Animal Quiz</b></b-nav-item>
        <b-nav-item disabled>Counter: {{numCorrect}}/{{numTotal}}</b-nav-item>
      </b-nav>
    </div>
</template>

<script>
export default {
  props: [
    'numCorrect',
    'numTotal'
  ]
}
</script>

<style scoped>
.nav-item{
  margin: 0 30px 5px;
}

.nav{
 
}
</style>