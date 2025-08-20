<script setup>
    const props = defineProps(['tarefasPendentes'])

</script>
<template>
    <header class="p-5 mb-4 mt-4 bg-light roundend-3">
        <h1>Minhas Tarefas</h1>
        <!-- O Filtro abaixo pode ser colocado para contar a quantidade de produtos com aquela nomenclatura -->
        <p>
            Você possui {{ props.tarefasPendentes }} tarefas pendentes
        </p>
        </header>
</template>