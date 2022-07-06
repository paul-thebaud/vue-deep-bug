<template>
    <AppChild />
</template>

<script>
import AppChild from './AppChild.vue';

export default {
    name: 'App',
    components: { AppChild },
};
</script>

<style scoped>
:deep(.app-child__hello) {
    color: red;
}
</style>
