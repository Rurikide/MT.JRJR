<template>
  <div class="main">
    <p>Salut</p>
    <NuxtLogo />
    <br></br>
    <NuxtLink to="/plaza">Entre the Plaza</NuxtLink>
    <p></p>
    <NuxtLink to="/user">User</NuxtLink>
    <Intro />
    <Test />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-property-decorator';
import NuxtLogo from '~/components/NuxtLogo.vue';
import Intro from '~/components/Intro.vue';
import Test from '~/components/Test.vue';

export default Vue.extend({
    name: "IndexPage",
    components: { NuxtLogo, Intro, Test }
})
</script>


<style scoped>

.main {
color: indigo;
background-color: aquamarine;
font-size: 20px;
}
</style>