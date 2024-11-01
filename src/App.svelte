<script lang="ts">
  let count = $state(0)
</script>

<div class="felx-gap">
  <input type="number" bind:value={count} disabled>
  <button on:click={() => count ++}>count is {count}</button>
</div>


<style>
  div {
    background-color: #5B676D;
    border-radius: 30px
  }
  .felx-gap {
    display: flex;
    gap: 10px;
  }
  button {
    padding: 10px;
    text-align: center;
    font-family: 'Times New Roman', serif;
    font-size:60px
  }
  input {
    padding: 2px;
    text-align: center;
    font-family: 'Times New Roman', serif;
    font-size:50px
    
  }
</style>