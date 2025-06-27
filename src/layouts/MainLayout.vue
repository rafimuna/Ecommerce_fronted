<template>
  <q-layout view="hHh lpR fFf">
    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title class="text-bold">🛒 My Shop</q-toolbar-title>
        <q-btn flat label="Products" to="/" />
        <q-btn flat label="Add Product" to="/add" />
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup></script>
