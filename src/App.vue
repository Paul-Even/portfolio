<template>
  <v-app>
    
    <v-main>
      
      <Home_/>
      <router-view></router-view>

    </v-main>
  </v-app>
</template>

<script>
import Home_ from '@/components/Home.vue';


export default {
  name: 'App',

  components: {
    Home_,
  },

  data: () => ({
    //
  }),
};
</script>
