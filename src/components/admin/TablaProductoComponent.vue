<template>
    <h1>Tabla Componente de Producto</h1>
    <DataTable :value="props.data">
        <Column field="id" header="ID"></Column>
        <Column field="nombre" header="NOMBRE"></Column>
        <Column field="precio" header="PRECIO"></Column>
        <Column field="stock" header="STOCK"></Column>
    </DataTable>

</template>
<script setup>
    const props = defineProps(['nombre', 'data'])
</script>
