<script lang="ts">
  import Button from './Button.svelte';
  import Apple from './icons/Apple.svelte';
</script>

<header class="w-full max-w-[1200px] mx-auto px-6 py-6 flex items-center justify-between">
  <div class="font-bold text-xl tracking-tight">Toddle</div>
  <Button>
    <Apple className="w-4 h-4" />
    <span>Download for iOS</span>
  </Button>
</header>
