<script setup>
// FAMILLE VISEE : https_page_links_to_http_javascript
// script charge en http.
useHead({
    title: 'Parcours Noyaru — test de script JavaScript en contenu mixte',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page du parcours d\'obstacles Noyaru : teste le cas mixed-js, un script charge en HTTP sur une page HTTPS pour declencher uniquement cette anomalie de contenu' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours Noyaru — test de script JavaScript en contenu mixte' },
      { property: 'og:description', content: 'Page du parcours d\'obstacles Noyaru : teste le cas mixed-js, un script charge en HTTP sur une page HTTPS pour declencher uniquement cette anomalie de contenu' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/mixed-js/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours Noyaru — test de script JavaScript en contenu mixte' },
      { name: 'twitter:description', content: 'Page du parcours d\'obstacles Noyaru : teste le cas mixed-js, un script charge en HTTP sur une page HTTPS pour declencher uniquement cette anomalie de contenu' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/mixed-js/' }
    ],
    script: [
      { src: 'https://noyaru-stack-nuxt.netlify.app/app.js' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : mixed js</h1>
    <p>Cette page du parcours traite le cas « mixed js ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
