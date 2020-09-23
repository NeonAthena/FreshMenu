<template>
<v-container>
<v-row class="my-10">
<v-col 
cols="12"
md="4">
  <v-hover v-slot:default="{ hover }">
    <v-card
      class=""
      color=""
      max-width="500"
      max-height="5"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://images.unsplash.com/photo-1509680859026-7d8cfc6894f4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>WOK STATION</b></font>
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
      max-height="5"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://images.unsplash.com/photo-1552590635-27c2c2128abf?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>BIRYANI</b></font>
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
      max-height="5"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://images.unsplash.com/photo-1574126154517-d1e0d89ef734?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1934&q=80"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>PIZZA</b></font>
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