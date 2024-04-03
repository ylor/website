<script>
  Array.prototype.random = function () {
    return this[Math.floor(Math.random() * this.length)];
  };

  const facts = [
    "accepts credit, not blame",
    "breath of the wild fanboy",
    "dark mode enthusiast",
    "grug brained",
    "knows enough to get into trouble, but not necessarily out of it",
    "neon genesis evangelion evangelist",
    "occasional grass toucher",
  ];
  const fact = facts.random()
</script>

<header>
  <h1>roly reyes</h1>
  <span>{fact}</span>
</header>

<style>
  h1 {
    font-family: system-ui, sans-serif;
    text-transform: uppercase;
  }
  span {
    font-family: Charter, "Bitstream Charter", "Sitka Text", Cambria, serif;
    font-style: italic;
    font-weight: normal;
  }
</style>
