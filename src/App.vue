
<template>
  <v-app>
   
   <v-toolbar app>
     <v-toolbar-title>TUKIAPP</v-toolbar-title>
   </v-toolbar>
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>


<script>

import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
