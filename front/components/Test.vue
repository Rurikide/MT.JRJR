<template>
    <p>{{ user }}</p>
</template>
  
<script lang="ts">
import { Vue, Component, Watch } from 'vue-property-decorator'

@Component  
export default class Test extends Vue {
  user: String = "Component Test.vue"; 
  
    
}
</script>

<style>

</style>