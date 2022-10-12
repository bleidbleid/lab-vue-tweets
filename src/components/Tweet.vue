<template>
    <div class="tweet">
        <ProfileImage :image="tweet.user.image" />
        <div class="body">
            <div class="top">
                <User :user="tweet.user"/>
                <Timestamp :time="tweet.timestamp" />
            </div>
            <Message :message="tweet.message" />
            <Actions />
        </div>
        <i class="fas fa-ellipsis-h"></i>
    </div>
</template>
<script setup>
// import { ref } from 'vue'
import { defineProps } from 'vue'
import ProfileImage from './ProfileImage.vue'
import User from './User.vue'
import Timestamp from './Timestamp.vue'
import Message from './Message.vue'

// Definimos los props que vamos a recibir en el componente
const props = defineProps(['tweet']);
</script>
  
<style scoped>
a {
    color: #42b983;
}
</style>