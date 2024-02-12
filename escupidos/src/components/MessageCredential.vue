<template>
    <div class="row">
        <img src="" alt="icono">
        <h3>Fabio</h3>
    </div>
</template>

<script lang="ts" setup>
    
    enum Tipo{TWITER, INSTAGRAM}

    interface Mensaje{
        tipo:Tipo,
        mensaje:string,
        remitente:string,
        destino:string,
        img:Blob
    }

</script>

<style scoped>
    .row{
        display: flex;
        flex-direction: row;
        padding: 30px;
    }
</style>