<script setup>
// FAMILLE VISEE : hreflang_defined_but_html_lang_missing
// hreflang declare mais <html> sans attribut lang.
useHead({
    title: 'Parcours d\'obstacles Noyaru - Hreflang No HTML Lang',
    htmlAttrs: { lang: 'fr' },  // langue définie pour hreflang
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique et immersive.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Page de test du parcours d\'obstacles Noyaru' },
      { property: 'og:description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique et immersive.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-no-html-lang/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Page de test du parcours d\'obstacles Noyaru' },
      { name: 'twitter:description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique et immersive.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-no-html-lang/' },
      { rel: 'alternate', hreflang: 'fr', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-no-html-lang/' },
      { rel: 'alternate', hreflang: 'x-default', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/hreflang-no-html-lang/' },
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
