<template>
    <v-app-bar app color="#111111" dark flat>
        
        
        <v-col cols="1">
            <v-img src="@/assets/hl_logo5.png" max-height="75px" div="logo" contain></v-img> 
        </v-col>
        <v-spacer></v-spacer>
        <v-spacer></v-spacer>
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
<style>

.logo{
    float: left;
    
}
</style>