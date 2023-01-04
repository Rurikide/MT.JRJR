<template>
    <p>{{ intro }}</p>
</template>
  
<script lang="ts">
import { Vue, Component, Watch } from 'vue-property-decorator'

@Component  
export default class Test extends Vue {
  intro: String = "Component Intro.vue"; 
  
    
}
</script>

<style>

</style>