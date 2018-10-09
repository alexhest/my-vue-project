<template>

  <footer>
    <p>  {{ footerText }} </p>
    <Button/>
  </footer>

</template>


<script>

  import Button from './Button.vue';

  export default {
    name: 'Footer',
    components: {
      Button
    },
    data () {
      return {
        footerText: 'Footer Component'
      }
    }
  }

</script>


<style lang="scss" scoped>

  footer {
    position: absolute;
    bottom: 0;
    width: 98%;
    background: #41B883;

    p {
      text-transform: uppercase;
      font-weight: bold;
    }
  }

</style>
