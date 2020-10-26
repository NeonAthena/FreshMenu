<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">

    <!--Header 
   While making-->
   
    
   <Navbar/> 
      
      <v-row>
   <Breadcrumbs/>
      </v-row>
     
      
     
    <!-- Tried using the loop for the images in Image main component-->
      <!-- Body -->
      <ImageMain/>
      
    
       
     
     
   
  
 
    </v-container>
   
    <v-content light>
      <nuxt /> 
    </v-content>
    
    
    
    <!-- Footer 
  Tried changing the spacing when refreshed-->
    <v-row>
   <v-footer 
      absolute
      app
      color="grey-darken" 
      class="md-6 xs-12"
      > 
      
      <v-container>
        <v-row>
          <v-col
            cols="12"
            sm="12"
            md="3"
            >
            <h4 style="color:#FFF176">COMPANY</h4>
            
            <v-divider></v-divider>
            <br>
            <font size="2">FAQ<br><br>
            About<br><br>
            Careers<br><br>
            Blog<br><br></font>
          </v-col>
          <v-col
            >
            <h4 style="color:#FFF176">HELP & CONTACT</h4>
            <v-divider></v-divider>
            <br>
            <font size="2"><v-icon>mdi-target</v-icon>Help Center<br><br>
            <v-icon>mdi-email</v-icon>Email Us<br><br>
            <v-icon>mdi-phone</v-icon>080-6824-5911<br><br></font>
          
          </v-col>
          <v-col
            cols="12"
            sm="4"
            md="3"
            
            >
            <h4 style="color:#FFF176">MORE FROM US</h4>
            <v-divider></v-divider>
            <br>
            <font size="2">Bulk/Party Order<br><br>
            Cake Order<br><br>
            FreshClub<br><br>
            Offers<br></br></font>
          </v-col>
            

          <v-col
            cols="12"
            sm="4"
            md="3"
            
            >
            
            <v-divider class="mt-6"></v-divider>
            




           
    <v-text>
 <v-row
          align="top"
          justify="end"
        >
          
              <v-text small class="mr-2">Terms</v-text>
            
          
              <v-text small class="ml-4">Privacy</v-text>

        </v-row>
        </v-text>

         
      <v-row class="mt-16 pt-16"
          align="end"
          justify="end"
          
        >
         

        
       
              <v-icon class="mb-1 ml-2" color="#3949AB">mdi-facebook</v-icon>
            
          
              <v-icon class="mb-1 ml-2" color="#64B5F6">mdi-twitter</v-icon>
           
            
              <v-icon class="mb-1 ml-2" color="#F06292">mdi-instagram</v-icon>
            
          
        </v-row>
      </v-col>
        </v-row>
      </v-container>
    </v-footer>
 </v-row>
 

  </v-app>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-instagram',
      ],
    }),
  }
</script>
  

  

  </v-app>


<script>
export default {}
</script>



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

