<script setup>
// FAMILLE VISEE : hreflang_to_non_canonical
// hreflang pointant vers une page dont le canonical est ailleurs.
useHead({
    title: 'Hreflang vers non-canonical - Parcours d\'obstacles Noyaru',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique qui met à l\'épreuve vos compétences.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Page de test du parcours d\'obstacles Noyaru' },
      { property: 'og:description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique qui met à l\'épreuve vos compétences.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-to-non-canonical/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Page de test du parcours d\'obstacles Noyaru' },
      { name: 'twitter:description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique qui met à l\'épreuve vos compétences.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-to-non-canonical/' },
      { rel: 'alternate', hreflang: 'fr', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-to-non-canonical/' },
      { rel: 'alternate', hreflang: 'en', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/canonical-other/' }
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
