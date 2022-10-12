<template>
                    <span class="timestamp">{{props.timestamp}}</span>
</template>
<script setup>
// import { ref } from 'vue'
import { defineProps } from 'vue'
// Definimos los props que vamos a recibir en el componente
const props = defineProps(['timestamp']);
</script>
<style scoped>
</style>