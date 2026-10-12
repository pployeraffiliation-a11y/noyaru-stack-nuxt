<script setup>
// FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions
// jumelle de duplicate-a.
useHead({
    title: 'Parcours Noyaru : duplicate-b, page jumelle en double titre',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Parcours d\'obstacles — page duplicate-b : jumelle de duplicate-a, elle sert a valider la detection des meta descriptions en double par le correcteur SEO.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Deux pages qui portent exactement le meme titre pour le test' },
      { property: 'og:description', content: 'Parcours d\'obstacles — page duplicate-b : jumelle de duplicate-a, elle sert a valider la detection des meta descriptions en double par le correcteur SEO.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-b/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Deux pages qui portent exactement le meme titre pour le test' },
      { name: 'twitter:description', content: 'Parcours d\'obstacles — page duplicate-b : jumelle de duplicate-a, elle sert a valider la detection des meta descriptions en double par le correcteur SEO.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-b/' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : duplicate b</h1>
    <p>Cette page du parcours traite le cas « duplicate b ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
