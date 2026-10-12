<script setup>
// FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions
// jumelle de duplicate-b : meme titre ET meme description.
useHead({
    title: 'Parcours Noyaru : duplicate-a, détection des titres en double',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page duplicate-a du parcours d\'obstacles Nuxt : première des deux jumelles créées pour déclencher la détection des meta descriptions en double' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours Noyaru : duplicate-a, détection des titres en double' },
      { property: 'og:description', content: 'Page duplicate-a du parcours d\'obstacles Nuxt : première des deux jumelles créées pour déclencher la détection des meta descriptions en double' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-a/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours Noyaru : duplicate-a, détection des titres en double' },
      { name: 'twitter:description', content: 'Page duplicate-a du parcours d\'obstacles Nuxt : première des deux jumelles créées pour déclencher la détection des meta descriptions en double' },
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
