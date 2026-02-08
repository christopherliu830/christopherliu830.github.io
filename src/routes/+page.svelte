<script lang="ts">
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="introduction">
  <div class="title">
    <h1>Chris Liu</h1>
    <p>| Founder of <a href="https://lletter.net">LLetter Studios.</a></p>
  </div>

  <section class="links">
    <p>
      <a href="https://github.com/christopherliu830">Github</a> |
      <a href="https://x.com/clyinko">X</a> |
      <a href="https://bsky.app/profile/chrisliu.dev">Bluesky</a>
    </p>
  </section>
</div>

<section>
  Currently working on a top-down arcade shooter in Zig. If you have, or are
  looking for, experience in game development and this interests you, please
  contact me!
</section>

<section>
  <h1>Game Jams</h1>
  <p>
    <a href="https://puffles.itch.io/a-tied-tale">A Tied Tale</a>: A
    physics-based 2D platformer in Unity. Runner-up in the 2021 College Game
    Jam.
  </p>
  <p>
    <a href="https://lletter.itch.io/momotraitor">Momotraitor</a>: A turn-based
    animal sacrifice RPG.
  </p>
</section>

<section>
  <h1>Projects</h1>
  <p>
    <a href="https://jlptcheck.com">JLPTCheck</a>: A Japanese proficiency test
    that adapts to the skill level of the taker.
  </p>
</section>

<style>
  .title h1 {
    font-weight: 600;
    font-family: "Geist Pixel Square";
    animation-name: animation;
    animation-duration: 4s;
    animation-timing-function: steps(4, jump-end);
    animation-iteration-count: infinite;
    margin: 0;
  }

  h1 {
    margin: 3em 0 0.4em 0;
    font-size: 1.4em;
    font-weight: 600;
  }

  .introduction {
    margin: 48px 0 48px 0;
  }

  .title {
    display: flex;
    flex-direction: row;
    align-items: baseline;
    gap: 6px;
  }

  @keyframes animation {
    0% {
      transform: translate(0, -8px);
    }
    50% {
      transform: translate(0, 8px);
    }
    100% {
      transform: translate(0, -8px);
    }
  }

  section {
    padding-bottom: 8px;
  }
</style>
