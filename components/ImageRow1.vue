<template>
<v-container>
<v-row>
<v-col 
cols="12"
md="4">
  <v-hover v-slot:default="{ hover }">
    <v-card
      class=""
      color=""
      max-width="500"
      max-height="175"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://curlytales.com/wp-content/uploads/2017/07/thali-food-india-e1500888181584-1280x720.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>INDIAN THALIS </b></font>
           </v-flex>
           </div>

          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-8"
        style="position: relative;"
      >
       
      </v-card-text>
    </v-card>
  </v-hover>
 </v-col>

 <v-col 
cols="12"
md="4">
  <v-hover v-slot:default="{ hover }">
    <v-card
      class=""
      color=""
      max-width="500"
      max-height="175"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://lh3.googleusercontent.com/proxy/XnJEEaLzrXsfzQ-qt4CsDgzppIACfH8YOdI3EMoJiUvO9pDykwg6ar4VIfiuzIHuKE4WMErivOscddexEqzrIjWAQ5zx54Q1iFZJRqdy3_UeIhlZLsWZYePPP1N8Nnp5qs4"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>CONTINENTAL </b></font>
           </v-flex>
           </div>

          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-8"
        style="position: relative;"
      >
       
      </v-card-text>
    </v-card>
  </v-hover>
 </v-col>

 <v-col 
cols="12"
md="4">
  <v-hover v-slot:default="{ hover }">
    <v-card
      class=""
      color=""
      max-width="500"
      max-height="175"
    >
      <v-img
        :aspect-ratio="16/9"
        src="Fit.jpeg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>FIT & FAB </b></font>
           </v-flex>
           </div>

          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-8"
        style="position: relative;"
      >

      
       
      </v-card-text>
    </v-card>
  </v-hover>
 </v-col>
 



</v-row>


  </v-container>
</template>