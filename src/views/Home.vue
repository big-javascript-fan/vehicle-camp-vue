<template>
    <div class="home">
        <img alt="Vue logo" src="../assets/logo.png" />
        <AppNavigation appTitle="Meal Prep" />
    </div>
</template>

<script>
// @ is an alias to /src
import AppNavigation from '@/components/AppNavigation.vue';

export default {
    name: 'home',
    components: {
        AppNavigation
    }
};
</script>
