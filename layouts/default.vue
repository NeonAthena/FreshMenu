<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
  
    <!--Header toolbar and breadcrumbs -->
    <Densetoolbar/>
    <Breadcrumbs/>
   
      
    <!-- Body 
    The overlay has been added-->
    
    
    
    <!--Footer--> 
    <v-container>
   <v-layout row wrap class="mx-5">
   <v-flex xs5 md.auto>
    <v-img src="Fit.jpeg" max-width="200" max-height="300">
    </v-img>
    </v-flex>
    
     <v-flex xs5 md.auto>
    <v-img src="Fit.jpeg" max-width="200" max-height="300">
    </v-img>
    </v-flex>
    </v-img>
    </v-layout>


    </v-container>
   
   
   


  </v-app>
</template>

<script>
export default {}
</script>

<style> 
  .white--text {
    border: 1px solid;
  }

   #inspire {
    background-color: white;
    color: black;
  }
</style>