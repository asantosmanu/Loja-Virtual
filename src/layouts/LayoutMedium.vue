<script setup>
import { RouterView } from 'vue-router';
import MediumAside from '../components/templates/medium/MediumAside.vue';
import MediumFooter from '../components/templates/medium/MediumFooter.vue';
import MediumHeader from '../components/templates/medium/MediumHeader.vue';
</script>

<template>
    <header>
        <MediumHeader />
    </header>
    <aside>
        <MediumAside />
    </aside>
    <main>
        <RouterView />
    </main>
    <footer>
        <MediumFooter />
    </footer>
</template>