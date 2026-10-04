<script setup>
// FAMILLE VISEE : css_redirects + page_has_redirected_css
// feuille de style chargee depuis une URL qui redirige.
useHead({
    title: 'Parcours d\'obstacles Noyaru — CSS chargée via une redirection',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Page de test Noyaru dédiée au cas « CSS via redirection » : la feuille de style est chargée depuis une URL qui redirige, déclenchant uniquement cette anomalie.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Parcours d\'obstacles Noyaru — CSS chargée via une redirection' },
      { property: 'og:description', content: 'Page de test Noyaru dédiée au cas « CSS via redirection » : la feuille de style est chargée depuis une URL qui redirige, déclenchant uniquement cette anomalie.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/redirected-css/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Parcours d\'obstacles Noyaru — CSS chargée via une redirection' },
      { name: 'twitter:description', content: 'Page de test Noyaru dédiée au cas « CSS via redirection » : la feuille de style est chargée depuis une URL qui redirige, déclenchant uniquement cette anomalie.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/redirected-css/' },
      { rel: 'stylesheet', href: '/style.css' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles : redirected css</h1>
    <p>Cette page du parcours traite le cas « redirected css ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
