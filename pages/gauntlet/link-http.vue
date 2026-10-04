<script setup>
// FAMILLE VISEE : https_page_has_internal_links_to_http
// lien interne ecrit en http.
useHead({
    title: 'Parcours d\'obstacles Noyaru — liens internes en HTTP',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page du parcours d\'obstacles Noyaru dédiée aux liens internes en HTTP : un seul défaut ciblé pour déclencher uniquement la famille https_page_has_internal_links_to_http.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours d\'obstacles Noyaru — liens internes en HTTP' },
      { property: 'og:description', content: 'Page du parcours d\'obstacles Noyaru dédiée aux liens internes en HTTP : un seul défaut ciblé pour déclencher uniquement la famille https_page_has_internal_links_to_http.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/link-http/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours d\'obstacles Noyaru — liens internes en HTTP' },
      { name: 'twitter:description', content: 'Page du parcours d\'obstacles Noyaru dédiée aux liens internes en HTTP : un seul défaut ciblé pour déclencher uniquement la famille https_page_has_internal_links_to_http.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/link-http/' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : link http</h1>
    <p>Cette page du parcours traite le cas « link http ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
    <p><a href="https://noyaru-stack-nuxt.netlify.app/a-propos">A propos</a></p>
  </main>
</template>
