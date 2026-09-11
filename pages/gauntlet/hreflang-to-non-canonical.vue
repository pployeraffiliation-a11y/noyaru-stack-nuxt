<script setup>
// FAMILLE VISEE : hreflang_to_non_canonical
// hreflang pointant vers une page dont le canonical est ailleurs.
useHead({
    title: 'Test hreflang vers page non-canonique | Noyaru',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page de test hreflang vers non-canonical : le lien alternate hreflang pointe vers une page dont l URL canonique est differente, afin de declencher cette anomalie precise.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Test hreflang vers page non-canonique | Noyaru' },
      { property: 'og:description', content: 'Page de test hreflang vers non-canonical : le lien alternate hreflang pointe vers une page dont l URL canonique est differente, afin de declencher cette anomalie precise.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-to-non-canonical/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Test hreflang vers page non-canonique | Noyaru' },
      { name: 'twitter:description', content: 'Page de test hreflang vers non-canonical : le lien alternate hreflang pointe vers une page dont l URL canonique est differente, afin de declencher cette anomalie precise.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-to-non-canonical/' },
      { rel: 'alternate', hreflang: 'fr', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-to-non-canonical/' },
      { rel: 'alternate', hreflang: 'en', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/canonical-http/' }
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
