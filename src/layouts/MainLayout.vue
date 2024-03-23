<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>
      <q-toolbar class="bg-red text-white shadow-2">
      <q-btn flat round dense icon="menu" class="q-mr-sm" />
      <q-separator dark vertical inset />

      <q-space />

      
      <q-separator dark vertical />
      <q-btn stretch flat label="About" />
      <q-separator dark vertical />
      <q-btn stretch flat label="Blog" />
    </q-toolbar>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup>
defineOptions({
  name: 'MainLayout'
})
</script>
