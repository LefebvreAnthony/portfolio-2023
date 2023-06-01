
<script setup>
import Menu from "@/components/Menu.vue";
import SideCard from "@/components/SideCard.vue";

const currentPage = "actu";
</script>

<template>
  <header>
    <Menu />
  </header>
  <main>
    <SideCard />
    <slot></slot>
  </main>
</template>
