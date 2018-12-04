<template>
  <div id="app">
    <Forms :fields="fields1"></Forms>
    <Forms :fields="fields2"></Forms>
  </div>
</template>

<script>
import Forms from './components/Forms.vue'

export default {
  name: 'app',
  data(){
    return{
      fields1:['text', 'radio', 'checkbox', 'submit'],
      fields2: ['text', 'text', 'checkbox', 'submit'],
      fields3: ['text', 'text', 'checkbox', 'submit'],
      fields4: ['text', 'text', 'checkbox', 'submit']

    }
  },
  components: {
    Forms
  }
}
</script>

<style>
*{
  text-align: center;
}

</style>
