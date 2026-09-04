<script setup>
const title = 'À propos : notre site de démo Nuxt pour vos tests et projets';
const description = "Site de test Nuxt : explorez cette page temoin saine et decouvrez un exemple concret de fixture Nuxt fonctionnelle. Consultez la demo des maintenant.";
const canonical = 'https://noyaru-stack-nuxt.netlify.app/a-propos/';

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
    <p>Page temoin : elle doit rester intacte apres la correction.</p>
  </main>
</template>
