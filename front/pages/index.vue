<template>
  <div class="main">
    <p>Salut</p>
    <NuxtLogo />
    <NuxtLink to="/user">User</NuxtLink>
    <Test />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-property-decorator';
import NuxtLogo from '~/components/NuxtLogo.vue';
import Test from '~/components/Test.vue';

export default Vue.extend({
    name: "IndexPage",
    components: { NuxtLogo, Test }
})
</script>


<style scoped>

.main {
color: red;
background-color: aquamarine;

}
</style>