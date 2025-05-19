<template>
    <nav class="bg-black text-white py-4 px-8 flex justify-between items-center">
        <h1 class="text-lg font-bold">
            Portifólio - Leonardo Navas
        </h1>
    <ul class = "flex gap-6">
        <li><router-link to="/" class="hover:underline">Inicio</router-link></li>
        <li><router-link to="/about" class="hover:underline">Sobre mim</router-link></li>
        <li><router-link to="/contact" class="hover:underline">Contato</router-link></li>
    </ul>
    </nav>
</template>