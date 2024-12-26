<script setup>
import ContactForm from "./contact/ContactForm.vue";
import ContactInfo from "./contact/ContactInfo.vue";
</script>

<template>
  <section class="p-4 py-20">
    <div class="mx-auto max-w-7xl w-full">
      <div class="grid lg:grid-cols-2 grid-cols-1 items-center">
        <contact-form />
        <contact-info />
      </div>
    </div>
  </section>
</template>

<style scoped></style>
