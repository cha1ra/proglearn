<template>
    <div>
        <v-toolbar
                color="indigo darken-4"
                dark
                tabs
        >
            <v-text-field
                    append-icon="mic"
                    class="mx-3"
                    flat
                    label="Search"
                    prepend-inner-icon="search"
                    solo-inverted
            ></v-text-field>

            <v-tabs
                    slot="extension"
                    v-model="tabs"
                    centered
                    color="transparent"
                    slider-color="white"
            >
                <v-tab
                        v-for="(language, index) in languages"
                        :key="index"
                >
                    {{ language }}
                </v-tab>
            </v-tabs>
        </v-toolbar>

        <v-tabs-items v-model="tabs">
            <v-tab-item
                    v-for="(language, index) in languages"
                    :key="index"
            >
                <v-card>
                    <v-card-text>
                        Comming soon ...
                    </v-card-text>
                </v-card>
            </v-tab-item>
        </v-tabs-items>
    </div>
</template>


<script>
    export default {
        data () {
            return {
                languages: [
                    "JavaScript",
                    "PHP",
                    "Python3",
                    "Swift4",
                    "Go"
                ]
            }
        }
    }
</script>
