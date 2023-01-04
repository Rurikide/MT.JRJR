<template>
  <div class="color">
    <p>{{ user }}</p>
  </div>
</template>
  
<script lang="ts">
import { Vue, Component, Watch } from 'vue-property-decorator'

@Component  
export default class User extends Vue {
  user: String = "COLOR PINK"; 
  
//  @Watch(user)
//  function name(params:int) {
    
}
</script>

<style>
.color {
  color: pink;
  background-color: black;
  height: 500px;
} 
</style>