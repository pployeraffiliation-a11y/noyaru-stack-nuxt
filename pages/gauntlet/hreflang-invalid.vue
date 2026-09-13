<script setup>
// FAMILLE VISEE : hreflang_annotation_invalid
// code de langue mal forme (soulignement au lieu du tiret).
useHead({
    title: 'Test hreflang invalide (code de langue mal forme) - Noyaru',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Test hreflang-invalid du parcours Noyaru : un code de langue mal forme (soulignement au lieu du tiret) declenche la detection des annotations hreflang invalides.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Test hreflang invalide (code de langue mal forme) - Noyaru' },
      { property: 'og:description', content: 'Test hreflang-invalid du parcours Noyaru : un code de langue mal forme (soulignement au lieu du tiret) declenche la detection des annotations hreflang invalides.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-invalid/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Test hreflang invalide (code de langue mal forme) - Noyaru' },
      { name: 'twitter:description', content: 'Test hreflang-invalid du parcours Noyaru : un code de langue mal forme (soulignement au lieu du tiret) declenche la detection des annotations hreflang invalides.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-invalid/' },
      { rel: 'alternate', hreflang: 'fr_FR', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-invalid/' }
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
