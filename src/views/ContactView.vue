<template>
  <div class="min-h-screen w-full flex flex-col items-center justify-center bg-white-50 relative px-4 py-8">
    <div class="w-full max-w-md p-6 bg-white rounded-md shadow-md">
      <h1 class="text-2xl font-bold mb-6 text-center">Deixe seu Feedback!!!</h1>

      <form class="space-y-5">
        <label class="block text-sm font-medium text-black">Completo:</label>
        <input type="text" placeholder="Nome Completo" class="w-full rounded-md border px-3 py-2"/>

        <label class="block text-sm font-medium text-black">Email:</label>
        <input type="email" placeholder="email@email.com" class="w-full rounded-md border px-3 py-2"/>

        <label class="block text-sm font-medium text-black">Mensagem:</label>
        <textarea rows="4" placeholder="Seu Feedback" class="w-full rounded-md border px-3 py-2"></textarea>

        <button type="submit" class="w-full bg-black text-white py-2 rounded-md hover:bg-gray-800 transition">
          Enviar
        </button>
      </form>
    </div>

    <div class="mt-8 flex flex-col items-center gap-4">
      <p class="text-black font-medium">Contate-me e veja meus projetos nas redes:</p>
      <div class="flex gap-6">
        <a href="https://www.linkedin.com/in/anthony-piovan-3a4029301/" class="flex justify-center items-center w-12 h-12 bg-white rounded-full shadow hover:scale-110 transition">
          <img src="@/assets/images/linkedin.png" alt="LinkedIn" class="w-6 h-6" />
        </a>
        <a href="https://github.com/AnthonyPiovanFourteen" class="flex justify-center items-center w-12 h-12 bg-white rounded-full shadow hover:scale-110 transition">
          <img src="@/assets/images/github.png" alt="GitHub" class="w-6 h-6" />
        </a>
      </div>
    </div>
  </div>
</template>
