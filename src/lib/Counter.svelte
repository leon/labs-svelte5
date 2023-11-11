<script lang="ts">
  let count = $state(0)
</script>

<button class="bg-blue-400 rounded p-4" on:click={() => count++}>
  clicks: {count}
</button>
