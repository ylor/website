<script>
  Array.prototype.random = function () {
    return this[Math.floor(Math.random() * this.length)];
  };

  const facts = [
    "breath of the wild fanboy",
    "dark mode enthusiast",
    "grug brained",
    "knows enough to get into trouble, but not necessarily out of it",
    "neon genesis evangelion evangelist",
    "occasional grass toucher",
  ];
</script>

<span>{facts.random()}</span>

<style>
  span {
    font-family: Charter, "Bitstream Charter", "Sitka Text", Cambria, serif;
    font-style: italic;
    font-weight: normal;
  }
</style>
