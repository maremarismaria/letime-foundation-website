<template>
  <header>
    <nav>
      <ul>
        <li class="site-title">El Letime | Asociación Cultural (<a class="link" href="https://es.wikipedia.org/wiki/El_Hierro" target="_blank">El Hierro</a>, Canarias)</li>
      </ul>
    </nav>
  </header>
  <main>
    <article>
      <div class="bg"></div>
      <h1>📌 Persevera, per severa, per se vera.</h1>
    </article> 
  </main>
  <footer>
    <ul>
      <li>&copy; {{ new Date().getFullYear() }} El Letime. Todos los derechos reservados.</li>
      <li>Photo by <a class="link" href="https://unsplash.com/@towfiqu999999?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Towfiqu barbhuiya</a> on <a class="link" href="https://unsplash.com/photos/Cv1IZqKJQzU?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a></li>
    </ul>
  </footer>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cutive+Mono&family=Kalam&family=Open+Sans:wght@300;400;500;700&family=VT323&display=swap');

* {
  box-sizing: border-box;
}

.bg {
  position: absolute;
  content: "";
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  background-image: url("/towfiqu-barbhuiya-Cv1IZqKJQzU-unsplash.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  opacity: 0.4;
  z-index: -1;
}

body, html {
  height: 100%;
}

body {
  margin: 0;
}

#__nuxt {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

#__nuxt nav {
  font-family: 'Open Sans', sans-serif;
}

#__nuxt li,
#__nuxt a.link {
  color: whitesmoke;
}

#__nuxt ul {
  list-style: none;
  padding: unset;
  margin: unset;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  padding: 1em;
  width: 100%;
  background: hsl(0, 0%, 7%);
  color: whitesmoke;
}

#__nuxt h1 {
  font-family: 'Open Sans', sans-serif;
}

#__nuxt header {
  margin-top: 0;
}

#__nuxt main {
  margin: auto 0;
}

#__nuxt main {
  height: 100%;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

#__nuxt main article {
  background: white;
  padding: 2em 4em;
}

#__nuxt footer {
  margin-top: auto;
  font-family: 'Open Sans', sans-serif;
}

#__nuxt footer ul {
  padding: 2em 1em;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

#__nuxt footer ul li {
  display: block;
}

#__nuxt footer ul li:not(:last-child) {
  margin-bottom: 0.8em;
}
</style>