<template>
    <v-container>
        <h1>Codictionary</h1>
        <search-bar />
    </v-container>
</template>
<script>
    import SearchBar from "~/components/SearchBar.vue"

    export default {
        components: {
            SearchBar
        }
    };
</script>
