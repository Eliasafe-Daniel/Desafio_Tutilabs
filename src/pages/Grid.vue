<template>
  <div class="grid">
    <FrameComponent2
      feitoPorBrunoPadding="var(--padding-smi) var(--padding-2xs-4)"
    />
    <main class="frame-parent"><FrameComponent4 /><FrameComponent3 /></main>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import FrameComponent2 from "../components/FrameComponent2.vue";
  import FrameComponent3 from "../components/FrameComponent3.vue";
  import FrameComponent4 from "../components/FrameComponent4.vue";
  export default defineComponent({
    name: "Grid",
    components: { FrameComponent2, FrameComponent4, FrameComponent3 },
  });
</script>

<style scoped>
  .frame-parent {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 26.5px;
    max-width: 100%;
  }
  .grid {
    width: 100%;
    position: relative;
    background-color: var(--bgmain);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-lg) var(--padding-xl) 66px;
    box-sizing: border-box;
    gap: var(--gap-2xl);
    line-height: normal;
    letter-spacing: normal;
  }
</style>
