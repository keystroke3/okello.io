<script setup lang="ts">
import Logo from './assets/okello.svg'
</script>

<template>
  <div class="main">
    <img :src="Logo" alt="logo" />
    <h1> Hola, I am Ted</h1>
    <h2>My Tools</h2>
    <ul class="tools">
      <li>
        <h3>ReURI</h3>
        <p>A tool to encode and decode URIs</p>
        <a href="https://reuri.okello.io" target="_blank" rel="noopener noreferrer">reuri.okello.io</a>
      </li>
      <li>
        <h3>Link A Stream</h3>
        <p>Find the stream link for many video platforms</p>
        <a href="https://linkastream.co" target="_blank" rel="noopener noreferrer">linkastream.co</a>
      </li>
    </ul>
    <h2>Socials</h2>
    <ul class="socials">
      <li>
        <p>Github</p>
        <a href="https://github.com/keystroke3" target="_blank" rel="noopener noreferrer">keystroke3</a>
      </li>
      <li>
        <p>Twitter</p>
        <a href="https://twitter.com/keystroke_3" target="_blank" rel="noopener noreferrer">keystroke_3</a>
      </li>
      <li>
        <p>My Dev Blog</p>
        <a href="https://dev.to/keystroke3" target="_blank" rel="noopener noreferrer">Dev.to/keystroke3</a>
      </li>
      <li>
        <p>Email</p>
        <a href="mailto:keystroke33@gmail.com">keystroke33@gmail.com</a>
      </li>
    </ul>
  </div>
</template>

<style scoped lang="scss">
.main {
  width: min(65vw, 70rem);
  // margin: auto;
}

.sep {
  width: inherit;
  border-bottom: 1px solid var(--color-fg);
}

.tools {
  li {
    min-width: 1fr;
  }
}

a {
  color: var(--color-green);
}

h1 {
  font-weight: 100;
  font-size: 4.7rem;
  // white-space: nowrap;
}

h2 {
  width: inherit;
  border-bottom: 1px solid hsl(240, 1.6%, 88.0%, 40%);
  font-weight: 300;
  font-size: 2rem;
  margin-top: 2rem;
}

h3 {
  font-weight: 300;
  font-size: 1.5rem;
}

ul {
  width: inherit;
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  column-gap: 5%;
}

li {
  font-size: 1.2rem;
  font-weight: 300;
  text-align: start;
  flex: 1;
  margin-block: 5%;
}
</style>
