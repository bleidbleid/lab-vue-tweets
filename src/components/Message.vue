<template>
    <p class="message">{{props.message}}</p>
</template>
<script setup>
// import { ref } from 'vue'
import { defineProps } from 'vue'
// Definimos los props que vamos a recibir en el componente
const props = defineProps(['message']);
</script>
<style scoped>
</style>