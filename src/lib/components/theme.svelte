<script lang="ts">
  import { Theme } from 'carbon-components-svelte'
  import type { CarbonTheme } from 'carbon-components-svelte/types/Theme/Theme.svelte'

  let theme: CarbonTheme
</script>

<Theme render="toggle" bind:theme persist persistKey="__carbon-theme" />

<style>
</style>
