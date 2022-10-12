<template>
            <img :src="props.image" alt="Placeholder image" class="profile"/>
</template>
<script setup>
import { defineProps } from 'vue'
// Definimos los props que vamos a recibir en el componente
const props = defineProps(['image']);
</script>
<style scoped>
</style>