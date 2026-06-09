<template>
  <section id="portfolio" class="py-24 bg-[#2A1A2D]">
    <div class="container mx-auto px-6 md:px-12">
      <!-- Section Header -->
      <div class="text-center mb-16">
        <span class="text-sm uppercase tracking-[0.3em] text-[#E94733] font-medium block mb-3">Nosso Acervo</span>
        <h2 class="text-3xl md:text-5xl font-serif text-white">Momentos <span class="italic text-[#E94733]">Eternizados</span></h2>
        <div class="w-16 h-[1px] bg-gradient-to-r from-[#E94733] to-[#EF8E27] mx-auto mt-6"></div>
      </div>

      <!-- Portfolio Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Item 1: Casamento -->
        <div class="group relative aspect-[3/4] overflow-hidden rounded-xl cursor-pointer">
          <img src="https://images.unsplash.com/photo-1511285560929-80b456fea0bc?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Casamento" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-black/10 to-transparent opacity-80 group-hover:opacity-90 transition-opacity"></div>
          <div class="absolute bottom-0 left-0 p-8 transform translate-y-4 group-hover:translate-y-0 transition-transform duration-500">
            <span class="text-[#EF8E27] text-xs uppercase tracking-widest mb-2 block">Casamento</span>
            <h3 class="text-white font-serif text-2xl">Lara & Rafael</h3>
          </div>
        </div>

        <!-- Item 2: Formatura -->
        <div class="group relative aspect-[3/4] overflow-hidden rounded-xl cursor-pointer lg:translate-y-12">
          <img src="https://images.unsplash.com/photo-1523580494863-6f3031224c94?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Formatura" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-black/10 to-transparent opacity-80 group-hover:opacity-90 transition-opacity"></div>
          <div class="absolute bottom-0 left-0 p-8 transform translate-y-4 group-hover:translate-y-0 transition-transform duration-500">
            <span class="text-[#EF8E27] text-xs uppercase tracking-widest mb-2 block">Formatura</span>
            <h3 class="text-white font-serif text-2xl">Medicina UFC</h3>
          </div>
        </div>

        <!-- Item 3: 15 Anos -->
        <div class="group relative aspect-[3/4] overflow-hidden rounded-xl cursor-pointer">
          <img src="https://images.unsplash.com/photo-1519741497674-611481863552?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="15 Anos" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-black/10 to-transparent opacity-80 group-hover:opacity-90 transition-opacity"></div>
          <div class="absolute bottom-0 left-0 p-8 transform translate-y-4 group-hover:translate-y-0 transition-transform duration-500">
            <span class="text-[#EF8E27] text-xs uppercase tracking-widest mb-2 block">15 Anos</span>
            <h3 class="text-white font-serif text-2xl">Baile da Sofia</h3>
          </div>
        </div>
        
        <!-- Item 4: Corporativo -->
        <div class="group relative aspect-[3/4] overflow-hidden rounded-xl cursor-pointer md:col-span-2 lg:col-span-1">
          <img src="https://images.unsplash.com/photo-1505362946560-8f13a7710b14?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Evento Corporativo" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-black/10 to-transparent opacity-80 group-hover:opacity-90 transition-opacity"></div>
          <div class="absolute bottom-0 left-0 p-8 transform translate-y-4 group-hover:translate-y-0 transition-transform duration-500">
            <span class="text-[#EF8E27] text-xs uppercase tracking-widest mb-2 block">Corporativo</span>
            <h3 class="text-white font-serif text-2xl">Gala Anual</h3>
          </div>
        </div>
      </div>

      <div class="text-center mt-16 lg:mt-24">
        <a href="#" class="inline-flex items-center gap-2 text-white hover:text-[#E94733] transition-colors font-medium uppercase tracking-widest text-sm border-b border-transparent hover:border-[#E94733] pb-1">
          Ver Galeria Completa
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
          </svg>
        </a>
      </div>
    </div>
  </section>
</template>
