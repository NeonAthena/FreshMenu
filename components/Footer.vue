<template>
 <v-footer 
      absolute
      app
      color="grey" 
      > 
      <span class="white--text">&copy; {{ new Date().getFullYear() }}</span>
      <v-container>
        <v-row>
          <v-col
            cols="12"
            sm="4"
            md="3"
            >
            <h3>COMPANY</h3>
            <v-divider></v-divider>
            <br><br>
            FAQ<br><br>
            About<br><br>
            Careers<br><br>
            Blog<br><br>
          </v-col>
          <v-col
            cols="12"
            sm="4"
            md="3"
            >
            <h3>HELP & CONTACT</h3>
            <v-divider></v-divider>
            <br><br>
            Help Center<br><br>
            Email Us<br><br>
            080-6824-5911<br><br>
          </v-col>
          <v-col
            cols="12"
            sm="4"
            md="3"
            >
            <h3>MORE FROM US</h3>
            <v-divider></v-divider>
            <br><br>
            Bulk/Part Order<br><br>
            Fresh Club<br><br>
            Offers<br><br>
            News Letter<br><br>
          </v-col>

          <v-col
            cols="10"
            md="10"
            >
            
            <v-divider></v-divider><br>
            <v-btn icon color="White">
              <v-icon large>mdi-facebook</v-icon>
            </v-btn>
            <v-btn icon color="White">
              <v-icon large>mdi-twitter</v-icon>
            </v-btn>
            <v-btn icon color="White">
              <v-icon large>mdi-instagram</v-icon>
            </v-btn>
           
            </v-btn>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
</template>