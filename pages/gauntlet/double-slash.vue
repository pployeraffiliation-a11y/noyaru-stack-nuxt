<script setup>
// FAMILLE VISEE : double_slash_in_url
// lien interne avec une double barre.
useHead({
    title: 'Double Slash - Test du parcours d\'obstacles Noyaru',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique et immersive.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Double Slash - Test du parcours d\'obstacles Noyaru' },
      { property: 'og:description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique et immersive.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/double-slash/' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Double Slash - Test du parcours d\'obstacles Noyaru' },
      { name: 'twitter:description', content: 'Découvrez le parcours d\'obstacles Noyaru, une expérience unique et immersive.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/double-slash/' }
    ],
});
</script>

<template>
  <main>
    <h1>Parcours d'obstacles</h1>
    <p>Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
    <p><a href="/">Retour a l accueil</a></p>
    <p><a href="//noyaru-stack-nuxt.netlify.app/a-propos">A propos</a></p>
  </main>
</template>
