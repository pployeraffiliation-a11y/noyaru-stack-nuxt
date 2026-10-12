<script setup>
// FAMILLE VISEE : duplicate_pages_without_canonical
// jumelle de no-canonical-a.
useHead({
    title: 'Deux pages jumelles sans canonical declare',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page jumelle B du parcours sans canonical : contenu identique a la page A pour provoquer la detection de doublon par la famille des pages dupliquees.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Deux pages jumelles sans canonical declare' },
      { property: 'og:description', content: 'Page jumelle B du parcours sans canonical : contenu identique a la page A pour provoquer la detection de doublon par la famille des pages dupliquees.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/no-canonical-b/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Deux pages jumelles sans canonical declare' },
      { name: 'twitter:description', content: 'Page jumelle B du parcours sans canonical : contenu identique a la page A pour provoquer la detection de doublon par la famille des pages dupliquees.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : pages jumelles</h1>
    <p>Cette page du parcours traite le cas « pages jumelles ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
