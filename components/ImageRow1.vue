<template>
<v-container>
<v-row>
<v-col 
cols="12"
md="4" sm="12">
  <v-hover v-slot:default="{ hover }">
    <v-card
      class="mb-16"
      color=""
      max-width="500"
      max-height="2"
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
md="4"
sm="12">
  <v-hover v-slot:default="{ hover }">
    <v-card
      class="my-sm-16 my-lg-0"
      color=""
      max-width="500"
      max-height="2"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://im.whatshot.in/content/2016/Sep/1473757744-forresta-rev.jpg"
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
md="4"
sm="12">
  <v-hover v-slot:default="{ hover }">
    <v-card
      class="my-sm-16 my-lg-0"
      color=""
      max-width="500"
      max-height="2"
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