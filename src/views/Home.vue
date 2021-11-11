<template>
<DataTable/>
</template>

<script lang="ts">
  import Vue from 'vue'
   import DataTable from '../components/DataTable/DataTable.vue'

  export default Vue.extend({
    name: 'Home',
components:{
DataTable
},
 
    data() {
      return {
        name:'mani'
      }
    },
  })
</script>
