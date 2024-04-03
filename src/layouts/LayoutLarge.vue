<script setup>
import { RouterView } from 'vue-router';
import LargeAside from '../components/templates/large/LargeAside.vue';
import LargeFooter from '../components/templates/large/LargeFooter.vue';
import LargeHeader from '../components/templates/large/LargeHeader.vue';
</script>

<template>
    <header>
        <LargeHeader />
    </header>
    <aside>
        <LargeAside />
    </aside>
    <main>
        <RouterView />
    </main>
    <footer>
        <LargeFooter />
    </footer>
</template>