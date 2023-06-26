<template>
  <div>
    <div class="flex justify-center">
      <h1 class="text-6xl text-white p-4">Projetos</h1>
    </div>

    <div
      class="flex flex-col items-center gap-8 pb-72 w-screen overflow-x-auto"
      id="projetos"
    >
      <div class="flex gap-10">
        <div class="bg-white w-96 p-2 rounded-lg text-center">
          <h2 class="p-2 font-semibold">Projeto Imobiliaria</h2>
          <img src="../assets/projetos/imob.png" alt="projeto 1" />
          <p class="p-2">Projeto para uma Imobiliaria.</p>
          <div class="flex flex-col gap-2">
            <p class="font-bold">Ferramentas</p>
            <div class="flex justify-center">
              <img src="../assets/react.png" alt="vue logo" width="20" />
            </div>
          </div>
        </div>
        <div class="bg-white w-96 p-2 rounded-lg text-center">
          <h2 class="p-2 font-semibold">Projeto TodoList</h2>
          <img src="../assets/projetos/todo.png" alt="projeto 2" />
          <p class="p-2">Projeto Lista de tarefas simples.</p>
          <div class="flex flex-col gap-2">
            <p class="font-bold">Ferramentas</p>
            <div class="flex justify-center">
              <img src="../assets/vue.png" alt="vue logo" width="20" />
            </div>
          </div>
        </div>
        <div class="bg-white w-96 p-2 rounded-lg text-center">
          <h2 class="p-2 font-semibold">Projeto Techno</h2>
          <img src="../assets/projetos/techno.png" alt="projeto 3" />
          <p class="p-2">Projeto Lista de tarefas simples.</p>
          <div class="flex flex-col gap-2">
            <p class="font-bold">Ferramentas</p>
            <div class="flex justify-center">
              <img src="../assets/vue.png" alt="vue logo" width="20" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
