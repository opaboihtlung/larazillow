<template>
<MainLayout>
    <div>Index</div>
    <Link href="/">Show Page</Link>
    <div>
        The message is {{ message }}
    </div>
</MainLayout>
</template>

<script setup>
    import { Link } from '@inertiajs/vue3'
    import MainLayout from '../../Layouts/MainLayout.vue'
    defineProps({
        message: String
    })
</script>