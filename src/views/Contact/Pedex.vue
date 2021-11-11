<template>
<div>
 <h1>This is a fucking Vue js Pedex</h1>

 <Snackbar/>
</div>
</template>

<script>
import Snackbar from '../../components/Snackbar/Snakbar.vue'

export default {
    name: 'Contact',

  components: {
    Snackbar
  },
  data() {
    return {
      contactData:'mani'
    }
  },
}
</script>
<style lang="">
    
</style>