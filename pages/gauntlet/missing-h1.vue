<script setup>
// FAMILLE VISEE : missing_h1
// aucun <h1> dans le corps.
useHead({
    title: 'Parcours d\'obstacles Noyaru — cas H1 absent à corriger',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page de test Noyaru dédiée au cas « H1 absent » : le corps ne contient aucun titre h1, provoquant uniquement cette anomalie lors du crawl de validation.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours d\'obstacles Noyaru — cas H1 absent à corriger' },
      { property: 'og:description', content: 'Page de test Noyaru dédiée au cas « H1 absent » : le corps ne contient aucun titre h1, provoquant uniquement cette anomalie lors du crawl de validation.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/missing-h1/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours d\'obstacles Noyaru — cas H1 absent à corriger' },
      { name: 'twitter:description', content: 'Page de test Noyaru dédiée au cas « H1 absent » : le corps ne contient aucun titre h1, provoquant uniquement cette anomalie lors du crawl de validation.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/missing-h1/' }
    ],
});
</script>

<template>
  <main>
    <p>Cette page du parcours traite le cas « missing h1 ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
