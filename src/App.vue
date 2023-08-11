<template>
  <div class="main">
    <img src="./assets/okello.svg" alt="logo" />
    <h1> Hola, I am Ted</h1>
    <p>A passionate software tools developer from Kenya. I build everything from automation scripts to APIs. I mainly work
      with Golang and Python.</p>
    <h2>What I have built </h2>
    <article class="highlight">
      <h3><a href="https://sala.pm" target="_blank" rel="noopener noreferrer">SALA.PM</a></h3>
      <p>Sala is an online scratchpad to store something you've copied somewhere that you want to continue with later.
        Each scratchpad is known as a Board and clips are added to it. Other devices can be added to the board to
        retrieve add more clips. <br>
        The backend is written in <strong>Golang</strong> and uses go websocket. The frontend is written in
        <strong>Typescript</strong> and built using
        <strong>Vue.js</strong><br><br>
        <a href="https://sala.pm" target="_blank" rel="noopener noreferrer"> Give it a try >>></a>
      </p>
      <img class="preview-img" src="./assets/sala-preview.png" alt="Sala preview">
    </article>
    <ul class="tools">
      <li>
        <h3><a href="https://reuri.okello.io" target="_blank" rel="noopener noreferrer">ReURI</a></h3>
        <p>A tool to encode and decode URIs</p>
        <p>It is written in Typescript and built using <strong>Vue.Js</strong></p><br>
        <a href="https://reuri.okello.io" target="_blank" rel="noopener noreferrer">reuri.okello.io >>></a>
      </li>
      <li>
        <h3><a href="https://linkastream.co" target="_blank" rel="noopener noreferrer">Link A Stream</a></h3>
        <p>Link A Stream has shut down, but it was a tool to get the direct stream url for almost any video platform</p>
        <p>It was written in javascript and built using Node.js with Express.js</p><br>
        <a href="https://github.com/keystroke3/linkastream" target="_blank" rel="noopener noreferrer">Look at the code
          >>></a>
      </li>
    </ul>
    <h2>My Blog</h2>
    <p id="blogtext">
      I have recently created a blog in Hugo called Recursive Heuristics.<br>
      It is still work in progress, but you can read a
      few of the articles I have written there.
      I plan on adding more content to it like my build logs for things I am working on, some interesting finds on the
      internet, and personal opinions.
      you can have a look at <br>
      <a id="bloglink" href="https://blog.okello.io" target="_blank" rel="noopener noreferrer">blog.okello.io >>></a>
    </p>
    <h2>How to reach me</h2>
    <ul class="socials">
      <li>
        <p>LinkedIn</p>
        <a href="https://www.linkedin.com/in/teddyokello/" target="_blank" rel="noopener noreferrer">/in/teddyokello</a>
      </li>
      <li>
        <p>Github</p>
        <a href="https://github.com/keystroke3" target="_blank" rel="noopener noreferrer">@keystroke3</a>
      </li>
      <li>
        <p>Twitter</p>
        <a href="https://twitter.com/keystroke_3" target="_blank" rel="noopener noreferrer">@keystroke_3</a>
      </li>
      <li>
        <p>Fediverse</p>
        <a href="https://mastodon.social/@SiliconRaven" target="_blank"
          rel="noopener noreferrer">@SiliconRaven@mastodon.social</a>
      </li>
      <li>
        <p>Email</p>
        <a href="mailto:contact@okello.io">contact@okello.io</a>
      </li>
    </ul>
  </div>
</template>

<style scoped lang="scss">
h1 {
  font-weight: 100;
  font-size: clamp(3rem, 4vw, 4.7rem);
  // white-space: nowrap;
}

h2 {
  width: inherit;
  border-bottom: 1px solid var(--color-fg);
  font-weight: 300;
  font-size: 2rem;
  margin-block: 2rem;
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
  font-weight: 300;
  text-align: start;
  flex: 1;
  margin-block: 5%;
}

.main {
  width: clamp(300px, 65vw, 70rem);
  // margin: auto;
}

.sep {
  width: inherit;
  border-bottom: 1px solid var(--color-fg);
}

.tools {
  li {
    min-width: 300px;
    background-color: var(--color-bg-alt);
    padding: 2%;
    border-radius: 10px;

  }
}

.highlight {
  min-width: max(300px, 100%);
  border-block: 2px solid var(--color-orange);
  border-radius: 15px;
  margin-bottom: 5%;
  background-color: var(--color-bg-alt);
  text-align: start;

  h3 {
    text-align: center;
    font-size: 2rem;
    font-style: bold;
  }

  p {
    padding: 2%;
  }


}

.preview-img {
  max-width: 100%;
  border-radius: inherit;
}

#bloglink {
  font-size: 1.5rem;
}

#blogtext {
  text-align: start;
}
</style>
