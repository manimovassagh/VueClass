<template>
<v-container>
  <v-data-table
    dense
    :headers="headers"
    :items="desserts"
    item-key="name"
    class="elevation-1"
  ></v-data-table>
</v-container>
</template>


<script src='./DataTable.ts'/>

