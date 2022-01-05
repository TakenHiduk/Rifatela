<style lang="scss">
  .span {
    @apply text-4xl;
    @apply font-bold;
    @apply text-sky-500;
    @apply transition-all;
    @apply duration-300;

    @apply dark_text-white;

    &:hover {
      @apply text-red-500;
    }

    &:active {
      @apply text-violet-500;
    }
  }
</style>

<script context="module">
</script>

<script lang="ts">
</script>

<svelte:head>
  <title>Rifatela</title>
</svelte:head>

<div class="flex justify-center items-center h-full w-full">
  <span class="span">Welcome to Home</span>
</div>
