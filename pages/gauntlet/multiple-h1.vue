<script setup>
// FAMILLE VISEE : multiple_h1
// deux <h1> sur la meme page.
useHead({
    title: 'Noyaru — parcours d\'obstacles : test avec plusieurs balises H1',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page de test Noyaru dédiée au cas « multiple H1 » : deux balises h1 coexistent sur la même page pour déclencher uniquement cette anomalie au crawl.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Page de test du parcours d\'obstacles Noyaru' },
      { property: 'og:description', content: 'Page de test Noyaru dédiée au cas « multiple H1 » : deux balises h1 coexistent sur la même page pour déclencher uniquement cette anomalie au crawl.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/multiple-h1/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Page de test du parcours d\'obstacles Noyaru' },
      { name: 'twitter:description', content: 'Page de test Noyaru dédiée au cas « multiple H1 » : deux balises h1 coexistent sur la même page pour déclencher uniquement cette anomalie au crawl.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/multiple-h1/' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : multiple h1</h1>
    <h1>Un second titre de niveau 1</h1>
    <p>Cette page du parcours traite le cas « multiple h1 ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
