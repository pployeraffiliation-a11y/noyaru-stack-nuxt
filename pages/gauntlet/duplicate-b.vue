<script setup>
// FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions
// jumelle de duplicate-a.
useHead({
    title: 'Page B du parcours d obstacles Noyaru : test de doublons',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page B du test de doublons : cette fixture illustre le second exemplaire du parcours d obstacles avec une meta description desormais unique et distincte.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Deux pages qui portent exactement le meme titre pour le test' },
      { property: 'og:description', content: 'Deux pages qui portent exactement la meme meta description, afin de declencher la famille des doublons.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-b/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Deux pages qui portent exactement le meme titre pour le test' },
      { name: 'twitter:description', content: 'Deux pages qui portent exactement la meme meta description, afin de declencher la famille des doublons.' },
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
