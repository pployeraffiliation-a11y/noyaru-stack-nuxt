<script setup>
// FAMILLE VISEE : https_page_links_to_http_css
// feuille de style chargee en http.
useHead({
    title: 'Parcours d\'obstacles Noyaru — CSS mixte HTTP/HTTPS',  
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page du parcours d\'obstacles Noyaru : cas « mixed-css », feuille de style chargée en HTTP sur une page HTTPS, afin de tester cette seule anomalie.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Page de test du parcours d\'obstacles Noyaru' },
      { property: 'og:description', content: 'Page du parcours d\'obstacles Noyaru : cas « mixed-css », feuille de style chargée en HTTP sur une page HTTPS, afin de tester cette seule anomalie.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/mixed-css/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Page de test du parcours d\'obstacles Noyaru' },
      { name: 'twitter:description', content: 'Page du parcours d\'obstacles Noyaru : cas « mixed-css », feuille de style chargée en HTTP sur une page HTTPS, afin de tester cette seule anomalie.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/mixed-css/' },
      { rel: 'stylesheet', href: 'https://noyaru-stack-nuxt.netlify.app/style.css' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : mixed css</h1>
    <p>Cette page du parcours traite le cas « mixed css ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
