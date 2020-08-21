<template>
  <div class="home">
    <TradingViewComponent />
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" /> -->
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
// import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import TradingViewComponent from '@/components/TradingViewComponent.vue'

@Component({
  components: {
    // HelloWorld,
    TradingViewComponent
  }
})
export default class Home extends Vue {}
</script>
