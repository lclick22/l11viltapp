<template>
    <div>This is INDEX page.</div>
    <Link href="/show">Show Page</Link>
    <div>The message is: {{ message }}</div>
</template>
<script setup>
    import { Link } from '@inertiajs/vue3';
    defineProps({
        message: String
    });
</script>
<script>
    import MainLayout from '../../Layouts/MainLayout.vue';
    export default {
        layout: MainLayout
    }
</script>