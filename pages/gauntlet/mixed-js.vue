<script setup>
// FAMILLE VISEE : https_page_links_to_http_javascript
// script charge en http.
useHead({
    title: 'Parcours d\'obstacles Noyaru — script mixte HTTP et HTTPS',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page du parcours d\'obstacles Noyaru : cas « mixed-js », un script charge en HTTP sur une page HTTPS. Toutes les autres balises sont conformes pour isoler cette anomalie.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours d\'obstacles Noyaru — script mixte HTTP et HTTPS' },
      { property: 'og:description', content: 'Page du parcours d\'obstacles Noyaru : cas « mixed-js », un script charge en HTTP sur une page HTTPS. Toutes les autres balises sont conformes pour isoler cette anomalie.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/mixed-js/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours d\'obstacles Noyaru — script mixte HTTP et HTTPS' },
      { name: 'twitter:description', content: 'Page du parcours d\'obstacles Noyaru : cas « mixed-js », un script charge en HTTP sur une page HTTPS. Toutes les autres balises sont conformes pour isoler cette anomalie.' },
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
