<template>
    <div class="color">
      <p>{{ plaza }}</p>
    </div>
  </template>
    
  <script lang="ts">
  import { Vue, Component, Watch } from 'vue-property-decorator'
  
  @Component  
  export default class Plaza extends Vue {
    plaza: String = "WELCOME TO THE PLAZA"; 
    
  //  @Watch(user)
  //  function name(params:int) {
      
  }
  </script>
  
  <style>
  .plaza {
    color: pink;
    background-color: black;
    height: 500px;
  } </style>