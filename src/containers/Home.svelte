<script lang="ts">
  import Button from '$components/Button.svelte'

  let example = import.meta.env.VITE_EXAMPLE
</script>

<main class="container mx-auto py-20">
  <p class="italic text-center">Home content here</p>
  <Button on:click={() => alert('hi')}>Say hi</Button>
  <Button on:click={() => alert('Emanuele')} type="secondary">To me</Button>
  <p>
    Your env variable: {example}
  </p>
</main>
