<template>
  <div class="fixed-center text-center">
    <h3 class="text-faded">Sobre mim</h3>
    <p>
      Amante da tecnologia. Uso o Vue.js a 6 meses e recentemente comecei a estudar o Quasar Framework. Num primeiro momento ele parece ser promissor.
    </p>
    <q-btn
      color="secondary"
      style="width:200px;"
      @click="$router.push('/')"
    >Go back</q-btn>
  </div>
</template>

<script>
export default {
  name: 'Sobre'
}
</script>