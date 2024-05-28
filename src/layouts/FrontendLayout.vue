<script setup lang="ts">
    import FrontendNav from '@/components/frontend/FrontendNav.vue'
    import FrontendFoot from '@/components/frontend/FrontendFoot.vue'
</script>

<template>
    <div>
        <FrontendNav />
        <main>
            <router-view />
        </main>
        <FrontendFoot />
    </div>
</template>

<style scoped>

</style>