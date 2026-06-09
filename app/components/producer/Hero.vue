<template>
  <section class="relative min-h-screen flex items-center pt-24 overflow-hidden bg-[#FAFAFA]">
    <!-- Elementos Decorativos de Fundo -->
    <div class="absolute top-0 right-0 w-1/2 h-full bg-[#FFF5F0] rounded-l-[100px] opacity-30 blur-3xl -z-0"></div>
    <div class="absolute bottom-[-10%] left-[-10%] w-96 h-96 bg-gradient-to-r from-[#E94733] to-[#EF8E27] rounded-full opacity-10 blur-3xl -z-0"></div>

    <div class="container mx-auto px-6 md:px-12 relative z-10">
      <div class="flex flex-col lg:flex-row items-center gap-16">
        
        <!-- Conteúdo Texto (Esquerda) -->
        <div class="lg:w-1/2 text-center lg:text-left mt-12 lg:mt-0">
          <div class="inline-block mb-4 px-4 py-1.5 rounded-full border border-[#E94733]/30 bg-gradient-to-r from-[#E94733] to-[#EF8E27]/5">
            <span class="text-xs uppercase tracking-[0.2em] text-[#E94733] font-medium">Desde 2012</span>
          </div>
          
          <h1 class="text-4xl md:text-5xl lg:text-6xl font-serif font-medium text-[#1A1A1A] leading-tight mb-6">
            A Arte de Celebrar com <br class="hidden md:block" />
            <span class="text-[#E94733] italic font-light relative">
              Elegância e Essência
              <svg class="absolute -bottom-2 left-0 w-full h-3 text-[#EF8E27] -z-10" viewBox="0 0 100 10" preserveAspectRatio="none">
                <path d="M0 5 Q 50 10 100 5" stroke="currentColor" stroke-width="4" fill="none" />
              </svg>
            </span>
          </h1>
          
          <p class="text-base md:text-lg text-gray-600 font-light leading-relaxed mb-10 max-w-lg mx-auto lg:mx-0">
            Organização e produção de eventos inesquecíveis. Cuidamos de cada detalhe com sensibilidade para que o seu grande dia seja perfeito.
          </p>
          
          <div class="flex flex-col sm:flex-row items-center gap-4 justify-center lg:justify-start">
            <a href="#contato" class="px-8 py-4 bg-gradient-to-r from-[#E94733] to-[#EF8E27] text-[#1A1A1A] rounded-full text-sm uppercase tracking-widest font-medium hover:from-[#D13D2B] hover:to-[#D47C20] transition-all shadow-lg shadow-[#E94733]/30 hover:shadow-xl hover:-translate-y-1 w-full sm:w-auto text-center">
              Começar a Planejar
            </a>
            <a href="#portfolio" class="px-8 py-4 bg-white text-[#1A1A1A] border border-[#E94733]/20 rounded-full text-sm uppercase tracking-widest hover:border-[#E94733] hover:text-[#E94733] transition-all w-full sm:w-auto text-center group flex justify-center items-center gap-2">
              Ver Portfólio
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 group-hover:translate-x-1 transition-transform" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
              </svg>
            </a>
          </div>

          <!-- Especialidades -->
          <div class="mt-12 flex items-center justify-center lg:justify-start gap-6 text-xs uppercase tracking-widest text-gray-500 font-medium">
            <span class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-[#FFF5F0]"></span> Casamentos</span>
            <span class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-[#FFF5F0]"></span> 15 Anos</span>
            <span class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-[#FFF5F0]"></span> Formaturas</span>
          </div>
        </div>

        <!-- Imagem (Direita) -->
        <div class="lg:w-1/2 relative">
          <div class="relative w-full max-w-md mx-auto aspect-[4/5] rounded-[2rem] overflow-hidden shadow-2xl shadow-[#E94733]/20 group">
            <img src="https://images.unsplash.com/photo-1519225421980-715cb0215aed?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80" alt="Decoração de Casamento Elegante" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-1000 ease-out" />
            <div class="absolute inset-0 bg-gradient-to-t from-black/40 to-transparent"></div>
            
            <!-- Badge Flutuante -->
            <div class="absolute bottom-6 left-6 right-6 bg-white/90 backdrop-blur-sm p-6 rounded-2xl border border-white/50 shadow-xl transform translate-y-2 opacity-0 group-hover:translate-y-0 group-hover:opacity-100 transition-all duration-500">
              <div class="flex items-center gap-4">
                <div class="w-12 h-12 bg-[#FFF5F0] rounded-full flex items-center justify-center text-[#E94733]">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                  </svg>
                </div>
                <div>
                  <h4 class="font-serif font-medium text-[#1A1A1A] text-lg">Amor em Detalhes</h4>
                  <p class="text-xs text-gray-600 font-sans mt-1">Sua história contada com perfeição.</p>
                </div>
              </div>
            </div>
          </div>
          
          <!-- Elemento decorativo flor / abstrato SVG (Opcional) -->
          <div class="absolute -top-10 -right-10 text-[#EF8E27] w-32 h-32 -z-10 animate-spin-slow">
            <svg viewBox="0 0 100 100" fill="currentColor">
              <path d="M50,0 C60,30 70,40 100,50 C70,60 60,70 50,100 C40,70 30,60 0,50 C30,40 40,30 50,0 Z" />
            </svg>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.animate-spin-slow {
  animation: spin 20s linear infinite;
}
@keyframes spin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}
</style>
