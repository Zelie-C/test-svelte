<script lang="ts">
  import Counter from './lib/Counter.svelte'
  let count: number = 0

  const increment = () => count += 1
  const decrement = () => count -= 1


</script>

<main>

  <h1>Compteur avec Svelte</h1>

  <div class="card">
    <Counter {count} {increment} />
    <button class="button button-parent" on:click={decrement}>Parent Decrement Button</button>
  </div>


</main>

<style>
</style>
