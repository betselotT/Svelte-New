<script>
  let count = 0;
  function increment() {
    count++;
  }
  function decrement() {
    count--;
  }
</script>

{count}

<button on:click={increment}> Count Up! </button>
<button on:click={decrement}> Count Down! </button>
