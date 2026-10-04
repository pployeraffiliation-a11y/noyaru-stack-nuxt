<script setup>
// FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions
// jumelle de duplicate-a.
useHead({
    title: 'Parcours obstacles Noyaru — variante B avec titre dupliqué',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Variante B du test de doublons Noyaru : cette page partageait sa description avec sa jumelle pour declencher la detection des meta descriptions dupliquees.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours obstacles Noyaru — variante B avec titre dupliqué' },
      { property: 'og:description', content: 'Variante B du test de doublons Noyaru : cette page partageait sa description avec sa jumelle pour declencher la detection des meta descriptions dupliquees.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/duplicate-b/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours obstacles Noyaru — variante B avec titre dupliqué' },
      { name: 'twitter:description', content: 'Variante B du test de doublons Noyaru : cette page partageait sa description avec sa jumelle pour declencher la detection des meta descriptions dupliquees.' },
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
