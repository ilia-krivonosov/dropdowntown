<template>
  <div>
    <VueMultiselect v-model="selectedOption" :options="options" label="name"></VueMultiselect>
  </div>
</template>

<script>
import VueMultiselect from 'vue-multiselect'

export default {
  components: {
    VueMultiselect
  },
  data() {
    return {
      selectedOption: null,
      options: [
        { name: 'Option 1' },
        { name: 'Option 2' },
        { name: 'Option 3' }
      ]
    }
  }
}
</script>

<style src="../assets/vue-multiselect.css"></style>