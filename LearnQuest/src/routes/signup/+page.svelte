<script>
  import Signup from "$components/Signup.svelte";
  import { Card } from "@sveltestrap/sveltestrap";
</script>

<style>
  .center-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh; /* Full viewport height */
    padding: 15px;
    background-color: black;
  }


</style>

<div class="center-container">
    <Signup/>
</div>
