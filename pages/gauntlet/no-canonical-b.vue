<script setup>
// FAMILLE VISEE : duplicate_pages_without_canonical
// jumelle de no-canonical-a.
useHead({
    title: 'Noyaru parcours : page B jumelle, contenu sans lien canonical',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page miroir sans canonical : jumelle de no-canonical-a, elle partage le meme contenu pour illustrer le cas des pages dupliquees sans balise canonique.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Deux pages jumelles sans canonical declare' },
      { property: 'og:description', content: 'Page miroir sans canonical : jumelle de no-canonical-a, elle partage le meme contenu pour illustrer le cas des pages dupliquees sans balise canonique.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/no-canonical-a/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Deux pages jumelles sans canonical declare' },
      { name: 'twitter:description', content: 'Page miroir sans canonical : jumelle de no-canonical-a, elle partage le meme contenu pour illustrer le cas des pages dupliquees sans balise canonique.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
  link: [
    { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/no-canonical-a/' }
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
