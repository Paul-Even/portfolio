<template>
    <v-app-bar app color="#111111" dark flat class="px-8">
        <v-btn icon height="50px">
            <v-icon color="#5F2369">mdi-brain</v-icon>
        </v-btn>
        <v-spacer></v-spacer>
        <v-btn text @click="scroll('home')">Home</v-btn>
        <v-btn text @click="scroll('about')">About</v-btn>
        <v-btn text @click="scroll('project')">Projects</v-btn>
        
        <v-btn text @click="scroll('contact')">Contact</v-btn>
    </v-app-bar>
</template>

<script>


export default {
    name: 'Navbar_',

    methods: {
        scroll(refName){
            const element = document.getElementById(refName);
            element.scrollIntoView({behaviour: "smooth"});
        }
    }
}
</script>
