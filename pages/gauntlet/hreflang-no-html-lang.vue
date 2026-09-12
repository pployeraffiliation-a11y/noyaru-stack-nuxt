<script setup>
// FAMILLE VISEE : hreflang_defined_but_html_lang_missing
// hreflang declare mais <html> sans attribut lang.
useHead({
    title: 'Parcours d\'obstacles Noyaru - Page de test unique',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique et immersive.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours d\'obstacles Noyaru - Page de test unique' },
      { property: 'og:description', content: 'Page du parcours d\'obstacles : elle est correcte partout sauf sur un point precis, afin que la famille visee soit la seule a se declencher au crawl.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-no-html-lang/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours d\'obstacles Noyaru - Page de test unique' },
      { name: 'twitter:description', content: 'Page du parcours d\'obstacles : elle est correcte partout sauf sur un point precis, afin que la famille visee soit la seule a se declencher au crawl.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-no-html-lang/' },
      { rel: 'alternate', hreflang: 'fr', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-no-html-lang/' },
      { rel: 'alternate', hreflang: 'en', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-to-non-canonical/' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles</h1>
    <p>Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
