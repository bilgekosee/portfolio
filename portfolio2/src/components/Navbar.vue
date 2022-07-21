<!-- eslint-disable vue/multi-word-component-names -->
<template>
<v-app-bar app color="#111111" dark flat class="px-8">
    <v-btn icon>
        <v-icon color="#6a040f">fas fa-dragon</v-icon>
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')">Ana Sayfa</v-btn>
    <v-btn text @click="scroll('project')">Proje</v-btn>
    <v-btn text @click="scroll('about')">Hakkımda</v-btn>
    <v-btn text @click="scroll('contact')">İletişim</v-btn>
</v-app-bar>
</template>

<script>
export default {
    methods: {
        scroll(refName) { 
            const element = document.getElementById(refName);
            element.scrollIntoView({behavior: "smooth"})
        }
    },

}
</script>

<style>

</style>