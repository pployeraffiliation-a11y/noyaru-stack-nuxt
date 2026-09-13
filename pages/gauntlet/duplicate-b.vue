<script setup>
// FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions
// jumelle de duplicate-a.
useHead({
    title: 'Parcours d obstacles Noyaru : page jumelle B (duplicate-b)',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page B du parcours d obstacles Noyaru : variante jumelle de duplicate-a, avec sa propre meta description unique pour eviter tout doublon au crawl.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours d obstacles Noyaru : page jumelle B (duplicate-b)' },
      { property: 'og:description', content: 'Page B du parcours d obstacles Noyaru : variante jumelle de duplicate-a, avec sa propre meta description unique pour eviter tout doublon au crawl.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-b/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours d obstacles Noyaru : page jumelle B (duplicate-b)' },
      { name: 'twitter:description', content: 'Page B du parcours d obstacles Noyaru : variante jumelle de duplicate-a, avec sa propre meta description unique pour eviter tout doublon au crawl.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-b/' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles</h1>
    <p>Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
