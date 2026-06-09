<template>
  <div class="min-h-screen bg-[#1E1220] text-white font-sans selection:bg-[#3D2640] selection:text-white">
    <ProducerDarkHeader />
    <main>
      <ProducerDarkHero />
      <ProducerDarkPortfolio />
      <ProducerDarkServicos />
      <ProducerDarkComoAjudamos />
      <ProducerDarkDepoimentos />
      <ProducerDarkContato />
    </main>
    <ProducerDarkFooter />
  </div>
</template>

<script setup>
import { useHead } from '#imports'

useHead({
  title: 'Producer Eventos | Assessoria e Cerimonial',
  meta: [
    { name: 'description', content: 'Organização e produção de eventos inesquecíveis. Formaturas, corporativos, casamentos e 15 anos em Fortaleza - CE.' }
  ],
  link: [
    { rel: 'preconnect', href: 'https://fonts.googleapis.com' },
    { rel: 'preconnect', href: 'https://fonts.gstatic.com', crossorigin: 'anonymous' },
    { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&family=Montserrat:wght@300;400;500;600&display=swap' }
  ]
})
</script>

<style>
/* Configurações Globais do Tema Delicado */
html {
  scroll-behavior: smooth;
}

.font-serif {
  font-family: 'Playfair Display', serif;
}

.font-sans, body {
  font-family: 'Montserrat', sans-serif;
}
</style>
