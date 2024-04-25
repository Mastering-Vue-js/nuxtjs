<script setup>
const route = useRoute();
</script>
<template>
    <div>
        <h1>Hello from single page, id: {{ route.params.id }}</h1>
    </div>
</template>