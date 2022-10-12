<template>
    <span class="user">
        <span class="name">{{props.user.name}}</span>
        <span class="handle">{{props.user.handle}}</span>
    </span>
</template>
<script setup>
import { defineProps } from 'vue'
// Definimos los props que vamos a recibir en el componente
const props = defineProps(['user']);
</script>
<style scoped>

</style>