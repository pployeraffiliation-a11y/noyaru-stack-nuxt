<script setup>
// FAMILLE VISEE : verifier_balises_canoniques
// Vérification des balises canoniques d'un site pour assurer un bon référencement.
useHead({
    title: 'Comment vérifier les balises canoniques d\'un site',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Cette page explique comment vérifier les balises canoniques d\'un site pour optimiser le référencement et éviter les problèmes de contenu dupliqué.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Comment vérifier les balises canoniques d\'un site' },
      { property: 'og:description', content: 'Cette page explique comment vérifier les balises canoniques d\'un site pour optimiser le référencement et éviter les problèmes de contenu dupliqué.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/comment-verifier-les-balises-canoniques-d-un-site' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Comment vérifier les balises canoniques d\'un site' },
      { name: 'twitter:description', content: 'Cette page explique comment vérifier les balises canoniques d\'un site pour optimiser le référencement et éviter les problèmes de contenu dupliqué.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/comment-verifier-les-balises-canoniques-d-un-site' }
    ],
});
</script>

<template>
  <main>
    <h1>Vérification des balises canoniques</h1>
    <p>Cette page fournit des conseils sur la manière de vérifier les balises canoniques d\'un site. Les balises canoniques sont essentielles pour indiquer aux moteurs de recherche quelle version d\'une page doit être indexée, évitant ainsi les problèmes de contenu dupliqué.</p>
    <p>Pour vérifier les balises canoniques, vous pouvez utiliser des outils comme les inspecteurs d\'éléments de votre navigateur ou des outils SEO spécialisés. Assurez-vous que chaque page a une balise canonique pointant vers l\'URL correcte.</p>
    <p><a href="/">Retour à l'accueil</a></p>
  </main>
</template>
