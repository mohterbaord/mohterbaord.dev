<template>
  <div id="app">
    {{yearsOfLife}}
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class App extends Vue {

  private get yearsOfLife(): string {
    return '2019\u20132020';
  }

}
</script>
