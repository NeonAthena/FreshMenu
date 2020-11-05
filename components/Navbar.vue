<template>
  <v-card class="overflow-hidden">
    <v-app-bar
      absolute
      color="black"
      dark
      shrink-on-scroll
      prominent
      src="https://payload.cargocollective.com/1/22/729184/12985187/01-03_1500.jpg"
      fade-img-on-scroll
      scroll-target="#scrolling-techniques-1"
    >
    <!-- started by card components andthen figured out the for loop. It was intially very difficult to align the text and the rating. For the overlay that takes place when an individual hovers over it, the opacity wasnt specied so just tried writing opacity and see it it works. It did work for the bg black rectangle overlay as well as the text-->
      <template v-slot:img="{ props }">
        <v-img
          v-bind="props"
          style="height: 100%; opacity: 52%; text-opacity: 100%"
          
        ></v-img>
      </template>

      <v-app-bar-nav-icon color="black"></v-app-bar-nav-icon>

      

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon color="black" medium>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon medium color="black">mdi-map-marker</v-icon>
      </v-btn>

      <v-menu
        bottom
        left
      >
        <template v-slot:activator="{ on, attrs }">
          <v-btn
            icon
            color="#FFFFF0"
            v-bind="attrs"
            v-on=""
          >
            <v-icon color="black" medium>mdi-cart</v-icon>
          </v-btn>
        </template>

        <v-list>
          <v-list-item
            v-for="(item, i) in items"
            :key="i"
          >
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>

    <!-- used v-dialog to add the pop up and a way for users to actively login and sign up without feeling burderned too by adding optimistic and encouraging titkes when opened.--> 

      <template v-slot:extension>
        <v-tabs align-bottom>
          <template>
  <v-row class="mx-3"justify="space-around" align="left">
    <v-dialog

      v-model="dialog"
      max-width="600px"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-btn
        
          color="Black"
          dark
          v-bind="attrs"
          v-on="on"
        >
          <Font color="orange">SIGN UP</font>
        </v-btn>
      </template>
      <v-card>
        <v-card-title>
          <span class="headline">Join us by signing up! :)</span>
        </v-card-title>
        <v-card-text>
          <v-container>
            <v-row>
              <v-col
                cols="12"
                sm="6"
                md="4"
              >
                <v-text-field
                  label="First Name*"
                  required
                ></v-text-field>
              </v-col>
              <v-col
                cols="12"
                sm="6"
                md="4"
              >
                <v-text-field
                  label="Middle Name*"
                  
                ></v-text-field>
              </v-col>
              <v-col
                cols="12"
                sm="6"
                md="4"
              >
                <v-text-field
                  label="Last Name*"
                
                  persistent-hint
                  required
                ></v-text-field>
              </v-col>
              <v-col cols="12">
                <v-text-field
                  label="Email*"
                  required
                ></v-text-field>
            
              </v-col>
              <v-col cols="12">
                <v-text-field
                  label="Password*"
                  required
                ></v-text-field>
              </v-col>
            </v-row>
          </v-container>
          <small>*indicates required field</small>
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          
          </v-btn>
          <v-btn
            color="orange"
            text
            @click="dialog = false"
          >
           SIGN UP
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>







    <v-dialog
    class="mx-3"
      v-model="dialog"
      max-width="600px"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-btn
        
          color="Black"
          dark
          v-bind="attrs"
          v-on="on"
        >
          <Font color="orange">LOGIN</font>
        </v-btn>
      </template>
      <v-card>
        <v-card-title>
          <span class="headline">Welcome Back! :)</span>
        </v-card-title>
        <v-card-text>
          <v-container>
            <v-row>
              <v-col
                cols="12"
                sm="6"
                md="4"
              >
                
              </v-col>
              <v-col cols="12">
                <v-text-field
                  label="Email*"
                  required
                ></v-text-field>
            
              </v-col>
              <v-col cols="12">
                <v-text-field
                  label="Password*"
                  required
                ></v-text-field>
              </v-col>



              <v-col cols="12" align="right">
                <v-btn>Forgot Password?</v-btn>
              </v-col>


            </v-row>
          </v-container>
          <small>*indicates required field</small>
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          
          </v-btn>
          <v-btn
            color="orange"
            text
            @click="dialog = false"
          >
           LOGIN
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>


    
  </v-row>

  











</template>








        </v-tabs>
      </template>
    </v-app-bar>
    <v-sheet
      id="scrolling-techniques-4"
      class="overflow-y-auto"
      max-height="300"
    >
      <v-container style="height: 220px;"></v-container>
    </v-sheet>
  </v-card>
</template>
