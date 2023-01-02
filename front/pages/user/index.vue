<template>
    <p>{{ user }}</p>
</template>
  
<script lang="ts">
import { Vue, Component, Watch } from 'vue-property-decorator'

@Component  
export default class User extends Vue {
  user: String = "salut user"; 
  
//  @Watch(user)
//  function name(params:int) {
    
}
</script>

<style>

</style>