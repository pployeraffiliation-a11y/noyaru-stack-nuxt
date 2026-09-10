<script setup>
// FAMILLE VISEE : hreflang_annotation_invalid
// code de langue mal forme (soulignement au lieu du tiret).
useHead({
    title: 'Hreflang Invalid - Parcours d\'obstacles Noyaru',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page de test pour le parcours d\'obstacles Noyaru, illustrant une anomalie spécifique.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Hreflang Invalid - Parcours d\'obstacles Noyaru' },
      { property: 'og:description', content: 'Page de test pour le parcours d\'obstacles Noyaru, illustrant une anomalie spécifique.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-invalid/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Hreflang Invalid - Parcours d\'obstacles Noyaru' },
      { name: 'twitter:description', content: 'Page de test pour le parcours d\'obstacles Noyaru, illustrant une anomalie spécifique.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-invalid/' },
      { rel: 'alternate', hreflang: 'fr-FR', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-invalid/' },
      { rel: 'alternate', hreflang: 'x-default', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-invalid/' }
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
