<script setup>
// FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions
// jumelle de duplicate-b : meme titre ET meme description.
useHead({
    title: 'Gauntlet duplicate-a : page avec titre en doublon Nuxt',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page duplicate-a du parcours d\'obstacles Nuxt : elle partage son titre avec duplicate-b pour déclencher exclusivement la famille des doublons SEO.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Gauntlet duplicate-a : page avec titre en doublon Nuxt' },
      { property: 'og:description', content: 'Page duplicate-a du parcours d\'obstacles Nuxt : elle partage son titre avec duplicate-b pour déclencher exclusivement la famille des doublons SEO.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-a/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Gauntlet duplicate-a : page avec titre en doublon Nuxt' },
      { name: 'twitter:description', content: 'Page duplicate-a du parcours d\'obstacles Nuxt : elle partage son titre avec duplicate-b pour déclencher exclusivement la famille des doublons SEO.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-a/' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : duplicate a</h1>
    <p>Cette page du parcours traite le cas « duplicate a ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
