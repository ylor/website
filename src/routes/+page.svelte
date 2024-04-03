<script>
  import Fact from "$lib/partials/Fact.svelte";

  Array.prototype.random = function () {
    return this[Math.floor(Math.random() * this.length)];
  };

  const bebop = [
    "are you living in the real world?",
    "do you have a comrade?",
    "easy come, easy go...",
    // "life is but a dream…",
    // "see you cowgirl, someday, somewhere!",
    "see you space cowboy…",
    // "see you space samurai…",
    // "sleeping beast",
    "you're gonna carry that weight.",
  ];
</script>

<main>
  <h1>roly reyes</h1>
  <Fact />
  <ul>
    <li>system engineer</li>
    <li>system administrator</li>
    <li>security analyst</li>
    <li>automation specialist</li>
  </ul>
</main>

<footer>{bebop.random()}</footer>

<style>
  h1 {
    font-family: system-ui, sans-serif;
    text-transform: uppercase;
  }

  ul {
    font-family: ui-monospace, "Cascadia Code", "Source Code Pro", Menlo,
      Consolas, "DejaVu Sans Mono", monospace;
  }

  footer {
    position: fixed;
    bottom: 8px;
    left: 8px;
    right: 8px;

    font-family: Charter, "Bitstream Charter", "Sitka Text", Cambria, serif;
    font-style: italic;
    text-transform: uppercase;
    font-size:small;
  }
</style>
