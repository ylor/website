<script>
  import random from "../actions/random.js"

  const facts = [
    "accepts credit, not blame",
    "breath of the wild fanboy",
    "charmingly garrulous",
    "dark mode enthusiast",
    "grug brained",
    "half-life 3 believer",
    "killjoy instalocker",
    "knows enough to be dangerous",
    "neon genesis evangelion evangelist",
    "occasional grass toucher",
  ];
  const fact = facts.random();
</script>

<header>
  <a href="/">
    <h1>roly reyes</h1>
  </a>
  <span>{fact}</span>
</header>

<style>
  a {
    color: inherit; /* blue colors for links too */
    text-decoration: inherit; /* no underline */
  }

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
