<script>
  let randomNumber = 0;

  function generateRandomNumber() {
    randomNumber = Math.floor(Math.random() * 100) + 1;
  }
</script>

<div>
  <h2>Random Number Generator</h2>
  <button on:click={generateRandomNumber}>Generate Random Number</button>
  <p>Random Number: {randomNumber}</p>
</div>
