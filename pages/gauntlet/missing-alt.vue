<script setup>
// FAMILLE VISEE : missing_alt_text
// image sans attribut alt.
useHead({
    title: 'Parcours d\'obstacles Noyaru — texte alternatif manquant',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page de test du parcours Noyaru dédiée au cas « alt manquant » : une image sans attribut alt est présente pour déclencher uniquement cette anomalie au crawl.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours d\'obstacles Noyaru — texte alternatif manquant' },
      { property: 'og:description', content: 'Page de test du parcours Noyaru dédiée au cas « alt manquant » : une image sans attribut alt est présente pour déclencher uniquement cette anomalie au crawl.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/missing-alt/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours d\'obstacles Noyaru — texte alternatif manquant' },
      { name: 'twitter:description', content: 'Page de test du parcours Noyaru dédiée au cas « alt manquant » : une image sans attribut alt est présente pour déclencher uniquement cette anomalie au crawl.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/missing-alt/' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : missing alt</h1>
    <p>Cette page du parcours traite le cas « missing alt ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
    <img :src="'/og.png'" />
  </main>
</template>
