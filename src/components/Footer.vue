<template>
    <v-footer dark padless>
        <v-card flat tile class="black white--text py-5 px-5 text-center" width="100%">
            <v-row>
                
                <v-col cols="12" sm="12">
                    <v-card-text class="pt-2">
                        <v-btn v-for="icon in icons" :key="icon" class="mx-1 white--text" icon>
                        <v-icon size="24px">{{ icon }}</v-icon>
                    </v-btn>
                    </v-card-text>
                </v-col>
                
            </v-row>
        </v-card>
    </v-footer>
</template>

<script>


export default {
    name: 'Footer_',
    data: ()=>({
        icons:[
            "mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"
        ]
    })
}
</script>
