<template>
    <div class = "msg-card">
        <MessageCredential/>
        <p>JHola mundo</p>
    </div>
</template>

<script lang="ts" setup>
    import MessageCredential from './MessageCredential.vue';
</script>

<style scoped>
    .msg-card{
        width: 80%;
        height: 80%;
        background-color: white;
        border-radius: 35px;
    }
</style>