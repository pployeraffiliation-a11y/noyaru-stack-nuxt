<script setup>
const title = 'Accueil du site de test Nuxt';
const description = "Page d'accueil du site fixture Nuxt utilise pour prouver la boucle complete de correction SEO, de l'injection au recrawl.";
const canonical = 'https://noyaru-stack-nuxt.netlify.app/';

// Nuxt idiom: head tags are declared with useHead(), never as raw HTML in the template.
useHead({
  title,
  meta: [
    { name: 'description', content: description },
    { property: 'og:type', content: 'website' },
    { property: 'og:title', content: title },
    { property: 'og:description', content: description },
    { property: 'og:url', content: canonical },
    { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
    { name: 'twitter:card', content: 'summary_large_image' },
    { name: 'twitter:title', content: title },
    { name: 'twitter:description', content: description },
    { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
  ],
  link: [{ rel: 'canonical', href: canonical }],
});
</script>

<template>
  <main>
    <h1>{{ title }}</h1>
    <p>Site fixture pour prouver la boucle complete sur la stack Nuxt.</p>
  </main>
</template>
