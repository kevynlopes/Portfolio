<template>
  <div
    class="flex justify-between sm:px-80 w-screen fixed bg-black/50 items-center max-md:justify-center py-2"
  >
    <img src="../assets/logo.png" alt="logo" class="sm:w-24 w-12" />
    <ul class="flex sm:gap-12 gap-6 items-center text-white">
      <li
        v-for="item in items"
        class="hover:text-white/60 cursor-pointer hover:scale-110 transition"
      >
        {{ item.message }}
      </li>
      <a
        href="#projetos"
        class="flex items-center bg-white text-black p-3 rounded-xl cursor-pointer hover:bg-slate-400 hover:scale-110 transition"
      >
        Projetos
      </a>
    </ul>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      items: [
        { message: "Inicio" },
        { message: "Sobre" },
        { message: "Contato" },
      ],
    };
  },
};
</script>
