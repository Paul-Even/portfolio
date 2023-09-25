<template>
    <v-footer dark padless>
        <v-card flat tile class="black white--text py-5 px-5 text-center" width="100%">
            <v-row>
                
                <v-col cols="12" sm="12">
                    <v-card-text class="pt-2">
                        <v-btn  class="mx-1 white--text" icon>
                            <a href="https://www.linkedin.com/in/paul-even/">
                            <v-icon 
                            x-large class="ml-3" color="#FFFFFF">
                                        mdi-linkedin
                                    </v-icon>
                                </a>

                                
                        
                    </v-btn>

                    <v-btn  class="mx-1 white--text" icon>
                            <a href="https://mail.google.com/mail/?view=cm&fs=1&to=pauleven95@gmail.com">
                            <v-icon 
                            x-large class="ml-3" color="#FFFFFF">
                                        mdi-gmail
                                    </v-icon>
                                </a>

                                
                        
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
            "mdi-gmail", "mdi-linkedin"
        ]
    })
}
</script>
