<template>
  <header>
    <h1>{{title}}</h1>
  </header>
  <main>
   <CaracEtAttribut/>
  </main>
</template>
<script>
import CaracEtAttribut from '../components/CaracEtAttribut.vue'
 export default {
  components: { CaracEtAttribut },
    data() {
      return {
        title : 'Chtulu'
      }
    },
  }
</script>
