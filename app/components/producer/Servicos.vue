<template>
  <section id="servicos" class="py-24 bg-[#FAFAFA] relative overflow-hidden">
    <!-- Decoração -->
    <div class="absolute top-40 left-0 w-64 h-64 bg-[#FFF5F0] rounded-full opacity-40 blur-3xl -z-0"></div>

    <div class="container mx-auto px-6 md:px-12 relative z-10">
      <div class="text-center mb-16">
        <span class="text-sm uppercase tracking-[0.3em] text-[#E94733] font-medium block mb-3">O que fazemos</span>
        <h2 class="text-3xl md:text-5xl font-serif text-[#1A1A1A]">Nossos <span class="italic text-[#E94733]">Serviços</span></h2>
        <div class="w-16 h-[1px] bg-gradient-to-r from-[#E94733] to-[#EF8E27] mx-auto mt-6"></div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Serviço 1 -->
        <div class="bg-white p-10 rounded-2xl shadow-sm border border-[#E94733]/20/50 hover:shadow-xl hover:shadow-[#E94733]/10 transition-all duration-500 group transform hover:-translate-y-2">
          <div class="w-16 h-16 bg-[#FAFAFA] rounded-full flex items-center justify-center mb-6 group-hover:bg-gradient-to-r from-[#E94733] to-[#EF8E27] transition-colors duration-500">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-[#E94733] group-hover:text-[#1A1A1A] transition-colors duration-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
            </svg>
          </div>
          <h3 class="font-serif text-2xl text-[#1A1A1A] mb-4">Casamentos</h3>
          <p class="text-gray-600 font-light text-sm leading-relaxed mb-6">
            Assessoria completa ou parcial para garantir que o seu grande dia seja fluido, emocionante e sem imprevistos.
          </p>
          <a href="#" class="text-[#E94733] text-xs uppercase tracking-widest font-medium hover:text-[#1A1A1A] transition-colors flex items-center gap-1">
            Saiba mais <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg>
          </a>
        </div>

        <!-- Serviço 2 -->
        <div class="bg-white p-10 rounded-2xl shadow-sm border border-[#E94733]/20/50 hover:shadow-xl hover:shadow-[#E94733]/10 transition-all duration-500 group transform hover:-translate-y-2">
          <div class="w-16 h-16 bg-[#FAFAFA] rounded-full flex items-center justify-center mb-6 group-hover:bg-gradient-to-r from-[#E94733] to-[#EF8E27] transition-colors duration-500">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-[#E94733] group-hover:text-[#1A1A1A] transition-colors duration-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
            </svg>
          </div>
          <h3 class="font-serif text-2xl text-[#1A1A1A] mb-4">Corporativo</h3>
          <p class="text-gray-600 font-light text-sm leading-relaxed mb-6">
            Eventos empresariais, congressos e confraternizações pensados para reforçar a imagem e cultura da sua marca.
          </p>
          <a href="#" class="text-[#E94733] text-xs uppercase tracking-widest font-medium hover:text-[#1A1A1A] transition-colors flex items-center gap-1">
            Saiba mais <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg>
          </a>
        </div>

        <!-- Serviço 3 -->
        <div class="bg-white p-10 rounded-2xl shadow-sm border border-[#E94733]/20/50 hover:shadow-xl hover:shadow-[#E94733]/10 transition-all duration-500 group transform hover:-translate-y-2">
          <div class="w-16 h-16 bg-[#FAFAFA] rounded-full flex items-center justify-center mb-6 group-hover:bg-gradient-to-r from-[#E94733] to-[#EF8E27] transition-colors duration-500">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-[#E94733] group-hover:text-[#1A1A1A] transition-colors duration-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
            </svg>
          </div>
          <h3 class="font-serif text-2xl text-[#1A1A1A] mb-4">Formaturas</h3>
          <p class="text-gray-600 font-light text-sm leading-relaxed mb-6">
            A celebração da sua conquista com festas grandiosas, bailes inesquecíveis e cerimônias impecáveis.
          </p>
          <a href="#" class="text-[#E94733] text-xs uppercase tracking-widest font-medium hover:text-[#1A1A1A] transition-colors flex items-center gap-1">
            Saiba mais <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg>
          </a>
        </div>

        <!-- Serviço 4 -->
        <div class="bg-white p-10 rounded-2xl shadow-sm border border-[#E94733]/20/50 hover:shadow-xl hover:shadow-[#E94733]/10 transition-all duration-500 group transform hover:-translate-y-2">
          <div class="w-16 h-16 bg-[#FAFAFA] rounded-full flex items-center justify-center mb-6 group-hover:bg-gradient-to-r from-[#E94733] to-[#EF8E27] transition-colors duration-500">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-[#E94733] group-hover:text-[#1A1A1A] transition-colors duration-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" />
            </svg>
          </div>
          <h3 class="font-serif text-2xl text-[#1A1A1A] mb-4">15 Anos</h3>
          <p class="text-gray-600 font-light text-sm leading-relaxed mb-6">
            Debutantes merecem uma noite mágica. Produzimos festas modernas ou tradicionais, sempre com muito glamour.
          </p>
          <a href="#" class="text-[#E94733] text-xs uppercase tracking-widest font-medium hover:text-[#1A1A1A] transition-colors flex items-center gap-1">
            Saiba mais <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
