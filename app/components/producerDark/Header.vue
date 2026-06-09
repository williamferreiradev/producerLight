<template>
  <header class="fixed w-full top-0 z-50 transition-all duration-300" :class="{ 'bg-[#1E1220]/90 backdrop-blur-md shadow-sm py-4': scrolled, 'bg-transparent py-6': !scrolled }">
    <div class="container mx-auto px-6 md:px-12 flex justify-between items-center">
      
      <!-- Logo -->
      <NuxtLink to="/producer" class="flex flex-col items-center group">
        <span class="font-serif text-2xl md:text-3xl font-semibold text-white tracking-wider group-hover:text-[#E94733] transition-colors">
          Producer<span class="text-[#E94733]">.</span>
        </span>
        <span class="text-[0.6rem] md:text-xs uppercase tracking-[0.2em] text-[#E94733] font-light mt-1">
          Eventos
        </span>
      </NuxtLink>

      <!-- Desktop Navigation -->
      <nav class="hidden md:flex space-x-8 items-center">
        <a v-for="link in links" :key="link.name" :href="link.href" class="text-sm uppercase tracking-widest text-white hover:text-[#E94733] transition-colors relative after:absolute after:-bottom-1 after:left-0 after:w-0 after:h-[1px] after:bg-gradient-to-r from-[#E94733] to-[#EF8E27] hover:after:w-full after:transition-all after:duration-300">
          {{ link.name }}
        </a>
        <a href="#contato" class="px-6 py-2 border border-[#E94733] text-[#E94733] hover:bg-[#3D2640] hover:border-[#E94733]/20 hover:text-white transition-all rounded-full text-sm uppercase tracking-widest">
          Fale Conosco
        </a>
      </nav>

      <!-- Mobile Menu Button -->
      <button @click="isMobileMenuOpen = !isMobileMenuOpen" class="md:hidden text-white focus:outline-none">
        <svg v-if="!isMobileMenuOpen" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
        <svg v-else xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>
    </div>

    <!-- Mobile Navigation -->
    <div v-show="isMobileMenuOpen" class="md:hidden absolute top-full left-0 w-full bg-[#1E1220] shadow-lg border-t border-[#E94733]/20">
      <nav class="flex flex-col py-4 px-6 space-y-4">
        <a v-for="link in links" :key="link.name" :href="link.href" @click="isMobileMenuOpen = false" class="text-sm uppercase tracking-widest text-white hover:text-[#E94733] transition-colors">
          {{ link.name }}
        </a>
        <a href="#contato" @click="isMobileMenuOpen = false" class="text-center px-6 py-3 bg-gradient-to-r from-[#E94733] to-[#EF8E27] text-white rounded-full text-sm uppercase tracking-widest mt-4">
          Fale Conosco
        </a>
      </nav>
    </div>
  </header>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const scrolled = ref(false)
const isMobileMenuOpen = ref(false)

const links = [
  { name: 'Portfólio', href: '#portfolio' },
  { name: 'Serviços', href: '#servicos' },
  { name: 'Como Ajudamos', href: '#como-ajudamos' },
  { name: 'Depoimentos', href: '#depoimentos' }
]

const handleScroll = () => {
  scrolled.value = window.scrollY > 50
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>
