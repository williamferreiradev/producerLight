<template>
  <section id="como-ajudamos" class="py-24 bg-[#2A1A2D] overflow-hidden">
    <div class="container mx-auto px-6 md:px-12">
      <div class="flex flex-col lg:flex-row items-center gap-16">
        
        <!-- Image Grid -->
        <div class="lg:w-1/2 relative">
          <!-- Background decoration -->
          <div class="absolute -top-8 -left-8 w-64 h-64 bg-[#3D2640] rounded-full opacity-50 blur-2xl"></div>
          
          <div class="relative z-10 grid grid-cols-2 gap-4">
            <div class="flex flex-col gap-4 pt-12">
              <img src="https://images.unsplash.com/photo-1519741497674-611481863552?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Detalhe Evento" class="rounded-2xl shadow-lg w-full h-48 object-cover" />
              <img src="https://images.unsplash.com/photo-1469334031218-e382a71b716b?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Equipe" class="rounded-2xl shadow-lg w-full h-64 object-cover" />
            </div>
            <div class="flex flex-col gap-4">
              <img src="https://images.unsplash.com/photo-1520854221256-17451cc331bf?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Cerimônia" class="rounded-2xl shadow-lg w-full h-72 object-cover" />
              <div class="bg-[#1E1220] rounded-2xl p-6 border border-[#E94733]/20 flex flex-col justify-center items-center text-center h-40">
                <span class="text-4xl font-serif text-[#E94733] mb-2">+12</span>
                <span class="text-xs uppercase tracking-widest text-white font-medium">Anos de Experiência</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Text Content -->
        <div class="lg:w-1/2">
          <span class="text-sm uppercase tracking-[0.3em] text-[#E94733] font-medium block mb-3">Nossa Essência</span>
          <h2 class="text-3xl md:text-4xl lg:text-5xl font-serif text-white leading-tight mb-6">
            Como Podemos <span class="italic text-[#E94733]">Te Ajudar?</span>
          </h2>
          
          <p class="text-gray-300 font-light leading-relaxed mb-6 text-lg">
            Sabemos que organizar um evento pode ser avassalador. Há inúmeros fornecedores, orçamentos, prazos e expectativas envolvidas. Nosso papel é ser o seu <strong>porto seguro</strong>.
          </p>
          
          <p class="text-gray-300 font-light leading-relaxed mb-10 text-lg">
            A Producer Eventos traz uma abordagem delicada, empática e altamente profissional. Absorcemos todo o estresse do planejamento para que você possa focar no que realmente importa: <span class="text-[#E94733] italic font-serif text-xl">viver o momento</span>.
          </p>

          <ul class="space-y-4 mb-10">
            <li class="flex items-start gap-4">
              <div class="w-6 h-6 rounded-full bg-[#3D2640] flex items-center justify-center mt-1 flex-shrink-0">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3 text-[#E94733]" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
              </div>
              <span class="text-white font-medium">Curadoria dos melhores fornecedores</span>
            </li>
            <li class="flex items-start gap-4">
              <div class="w-6 h-6 rounded-full bg-[#3D2640] flex items-center justify-center mt-1 flex-shrink-0">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3 text-[#E94733]" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
              </div>
              <span class="text-white font-medium">Gestão financeira e cronograma rigoroso</span>
            </li>
            <li class="flex items-start gap-4">
              <div class="w-6 h-6 rounded-full bg-[#3D2640] flex items-center justify-center mt-1 flex-shrink-0">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3 text-[#E94733]" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
              </div>
              <span class="text-white font-medium">Equipe feminina atenta aos mínimos detalhes</span>
            </li>
          </ul>

          <a href="#contato" class="inline-block px-8 py-4 bg-[#2A1A2D] text-white rounded-full text-sm uppercase tracking-widest font-medium hover:bg-gray-200 transition-all shadow-lg hover:-translate-y-1">
            Agendar Reunião
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
