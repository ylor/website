<script>
  import random from "../actions/random.js";

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

<footer>
  {bebop.random()}
</footer>

<style>
  footer {
    position: fixed;
    bottom: 8px;
    left: 8px;
    right: 8px;

    font-family: Charter, "Bitstream Charter", "Sitka Text", Cambria, serif;
    font-style: italic;
    font-weight: bolder;
    text-transform: uppercase;
    font-size: small;
  }
</style>