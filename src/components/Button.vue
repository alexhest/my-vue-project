<template>

  <button @click="click">
    {{ buttonText }}
  </button>

</template>


<script>

  import Button from './Button.vue';

  export default {
    name: 'Button',
    data () {
      return {
        buttonText: 'CLICK Button component'
      }
    },
    methods: {
      click () {
        alert('I am Button component :)')
      }
    }
  }
</script>


<style lang="scss" scoped>

  button {
    width: 200px;
    height: 100px;
    background: crimson;
    cursor: pointer;
    font-size: 20px;
  }

</style>
