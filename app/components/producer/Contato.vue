<template>
  <section id="contato" class="py-24 bg-[#130B14] relative">
    <div class="container mx-auto px-6 md:px-12">
      <div class="flex flex-col rounded-3xl overflow-hidden shadow-2xl shadow-[#E94733]/10 border border-[#E94733]/20 bg-[#1A0E1B] max-w-4xl mx-auto">
        
        <!-- Info Panel Centered -->
        <div class="p-12 md:p-16 flex flex-col justify-center items-center relative overflow-hidden text-center">
          <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-[#E94733] rounded-full opacity-10 blur-[100px]"></div>
          
          <div class="relative z-10 w-full">
            <span class="text-sm uppercase tracking-[0.3em] text-[#EF8E27] font-medium block mb-3">Atendimento</span>
            <h3 class="font-serif text-4xl md:text-5xl text-white mb-6">Vamos conversar?</h3>
            <p class="text-gray-300 font-light mb-12 max-w-2xl mx-auto text-lg">
              Estamos prontas para conhecer a sua história e ajudar a transformar seu evento em uma experiência inesquecível. Clique no botão abaixo e fale diretamente conosco.
            </p>

            <a href="https://wa.me/5585999999999" target="_blank" class="inline-flex items-center gap-3 px-10 py-5 bg-gradient-to-r from-[#E94733] to-[#EF8E27] text-white rounded-full text-sm uppercase tracking-widest font-bold hover:scale-105 transition-all shadow-lg shadow-[#E94733]/40">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.245 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.5-.669-.51l-.57-.01c-.198 0-.52.074-.792.347-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.876 1.213 3.074.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/>
              </svg>
              Conversar no WhatsApp
            </a>

            <div class="mt-16 grid grid-cols-1 md:grid-cols-3 gap-8 text-left border-t border-[#E94733]/20 pt-10">
              <div class="flex flex-col items-center text-center gap-3">
                <div class="w-12 h-12 rounded-full bg-[#2A162B] flex items-center justify-center flex-shrink-0 shadow-sm border border-[#E94733]/20">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-[#E94733]" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                </div>
                <div>
                  <h4 class="font-medium text-white">Nosso Escritório</h4>
                  <p class="text-gray-400 font-light text-sm mt-1">Fortaleza - CE</p>
                </div>
              </div>

              <div class="flex flex-col items-center text-center gap-3">
                <div class="w-12 h-12 rounded-full bg-[#2A162B] flex items-center justify-center flex-shrink-0 shadow-sm border border-[#E94733]/20">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-[#E94733]" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                  </svg>
                </div>
                <div>
                  <h4 class="font-medium text-white">Telefone</h4>
                  <p class="text-gray-400 font-light text-sm mt-1">(85) 99999-9999</p>
                </div>
              </div>

              <div class="flex flex-col items-center text-center gap-3">
                <div class="w-12 h-12 rounded-full bg-[#2A162B] flex items-center justify-center flex-shrink-0 shadow-sm border border-[#E94733]/20">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-[#E94733]" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                  </svg>
                </div>
                <div>
                  <h4 class="font-medium text-white">E-mail</h4>
                  <p class="text-gray-400 font-light text-sm mt-1">contato@producereventos.com.br</p>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
  </section>
</template>
