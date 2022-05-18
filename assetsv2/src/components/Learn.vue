<template>
  <div>
    <div>{{ msg }}</div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Learn extends Vue {
  @Prop({ default: "default value" })
  private msg: string;
}
</script>
