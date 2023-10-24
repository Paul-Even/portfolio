<template>
    <v-app-bar app color="#111111" dark flat> 
    
            <v-row>
                <v-col col="1" md="3" height ="100px" v-ripple="false">
                <div >
                    <v-btn height="67px" width="80px" href="https://pauleven.com" plain contain>
                        <v-img src="@/assets/PE_logo.png" class="l1" contain></v-img> 
                    </v-btn>
                </div>
                
                
                    
                </v-col>
                <v-col cols="2" md="4">
                        <v-btn height="57px" width="100px" href="https://dvic.devinci.fr/" target="_blank" plain contain>
                            <v-img src="@/assets/dvic_logo.png"  class="l2" contain></v-img>
                        </v-btn>
                        
                    
                    
                </v-col>
                <v-col cols="3" md="3">
                        <v-btn height="67px" width="150px" href="https://dvic.devinci.fr/groups/human-learning/" target="_blank" plain contain>
                            <v-img src="@/assets/hl_logo5.png"  class="l3" contain></v-img>
                        </v-btn>
                        
                    
                    
                </v-col>
                
                 
            </v-row>
            
        
        <v-spacer></v-spacer>
        <v-spacer></v-spacer>
        <v-spacer></v-spacer>
        <div color="white">
            <v-btn text @click="scroll('home')">Home</v-btn>
            <v-btn text @click="scroll('about')">About</v-btn>
            <v-btn text @click="scroll('project')">Projects</v-btn>        
            <v-btn text @click="scroll('contact')">Contact</v-btn>

        </div>
            
        
             
        
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
.l1{
    top:1px;
    width: 180px;
}
.l2{
    top: 8px;
    width: 10px;
    display: block;
    float: none;    
}
.l3{
    top: 1px;
    width: 150px;
    display: block;
    float: none;    
}

</style>