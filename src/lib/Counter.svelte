<script lang="ts">
  export let count: number
  export let increment: () => void

</script>

<button on:click={increment}>
  Increment : {count}
</button>
