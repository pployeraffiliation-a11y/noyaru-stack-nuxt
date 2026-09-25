<script setup>
// FAMILLE VISEE : aucune ; page de contenu editorial standard.
useHead({
    title: 'Comment verifier les balises canoniques d\'un site',
    htmlAttrs: { lang: 'fr' },
    meta: [
      { name: 'viewport', content: 'width=device-width' },
      { name: 'description', content: 'Guide pratique pour verifier les balises canoniques d\'un site : ou les trouver, quelles erreurs eviter et comment controler leur coherence lors du crawl.' },
      { property: 'og:type', content: 'article' },
      { property: 'og:title', content: 'Comment verifier les balises canoniques d\'un site' },
      { property: 'og:description', content: 'Guide pratique pour verifier les balises canoniques d\'un site : ou les trouver, quelles erreurs eviter et comment controler leur coherence lors du crawl.' },
      { property: 'og:url', content: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/comment-verifier-les-balises-canoniques-d-un-site' },
      { property: 'og:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' },
      { name: 'twitter:card', content: 'summary_large_image' },
      { name: 'twitter:title', content: 'Comment verifier les balises canoniques d\'un site' },
      { name: 'twitter:description', content: 'Guide pratique pour verifier les balises canoniques d\'un site : ou les trouver, quelles erreurs eviter et comment controler leur coherence lors du crawl.' },
      { name: 'twitter:image', content: 'https://noyaru-stack-nuxt.netlify.app/og.png' }
    ],
    link: [
      { rel: 'canonical', href: 'https://noyaru-stack-nuxt.netlify.app/gauntlet/comment-verifier-les-balises-canoniques-d-un-site' }
    ],
});
</script>

<template>
  <main>
    <h1>Comment verifier les balises canoniques d'un site</h1>
    <p>La balise canonique indique aux moteurs quelle URL doit etre consideree comme la version de reference d'un contenu. Une balise mal configuree peut faire disparaitre des pages de l'index ou concentrer l'autorite au mauvais endroit. Verifier ces balises est donc une etape essentielle d'un audit technique.</p>

    <h2>Ou se trouve la balise canonique</h2>
    <p>La balise se place dans la section &lt;head&gt; du document HTML sous la forme &lt;link rel="canonical" href="..."&gt;. Elle peut aussi etre envoyee via un en-tete HTTP Link, notamment pour les fichiers non HTML comme les PDF. Il faut donc controler les deux emplacements.</p>

    <h2>Verification manuelle</h2>
    <p>Ouvrez le code source d'une page et cherchez la ligne canonical. Verifiez que l'URL pointee est absolue, en HTTPS, sans parametres inutiles et qu'elle renvoie bien un statut 200. Une canonique qui pointe vers une page en 404 ou vers une redirection est une erreur frequente qui trouble le crawl.</p>

    <h2>Points a controler a grande echelle</h2>
    <ul>
      <li>Chaque page doit declarer une seule balise canonique.</li>
      <li>La cible doit exister et repondre en 200, jamais en 3xx ni en 4xx.</li>
      <li>La canonique auto-referente doit correspondre exactement a l'URL servie.</li>
      <li>Les variantes avec ou sans slash final doivent rester coherentes.</li>
      <li>Aucune canonique ne doit pointer vers un domaine different sans raison.</li>
    </ul>

    <h2>Automatiser le controle</h2>
    <p>Un crawler qui parcourt le site releve pour chaque URL la valeur de sa canonique, le statut de la cible et les eventuels conflits. C'est precisement ce que teste un parcours d'obstacles : provoquer une anomalie unique, comme une canonique vers une page absente, pour verifier que l'outil la detecte sans generer de faux positifs.</p>

    <p><a href="/">Retour a l accueil</a></p>
  </main>
</template>
