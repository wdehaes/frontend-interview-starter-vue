<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <main class="flex min-h-screen flex-col items-center justify-center">
    <div class="container flex flex-col items-center justify-center gap-12 px-4 py-16">
      <h1 class="text-5xl font-extrabold tracking-tight">Frontend Interview Starter</h1>
      <span>
        You can modify this code at
        <code
          class="bg-slate-800 hover:bg-slate-900 select-none text-white rounded-sm border-slate-900 border p-1"
          >/src/app/App.vue</code
        >.
      </span>
      <HelloWorld msg="hello world" />
    </div>
  </main>
</template>
