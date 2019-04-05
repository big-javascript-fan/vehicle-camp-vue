<template>
    <v-toolbar app color="brown darken-4" dark>
        <v-toolbar-side-icon class="hidden-md-and-up" @click="drawer = !drawer"></v-toolbar-side-icon>
        <v-spacer class="hidden-md-and-up"></v-spacer>
        <v-toolbar-title>{{appTitle}}</v-toolbar-title>
        <v-btn flat class="hidden-md-and-down">Menu</v-btn>
        <v-spacer class="hidden-md-and-down"></v-spacer>
        <v-btn flat class="hidden-md-and-down">SIGN IN</v-btn>
        <v-btn color="brow lighten-3" class="hidden-md-and-down">JOIN</v-btn>
    </v-toolbar>    
</template>

<script>
export default {
    name: 'AppNavigation',
    data() {
        return {
            appTitle: 'Meal Prep',
            drawer: false,
            items: [
                {title: 'Menu'},
                {title: 'Sign In'},
                {title: 'Join'}
            ]
        };
    }
};
</script>

<style scoped>

</style>
