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
        src="https://images.unsplash.com/photo-1586838488967-8ba28530505f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>SNACKS</b></font>
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
        src="https://images.unsplash.com/photo-1551024709-8f23befc6f87?ixlib=rb-1.2.1&auto=format&fit=crop&w=2850&q=80"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>BEVERAGE</b></font>
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
        src="https://images.unsplash.com/photo-1562634335-2f6a3668319d?ixlib=rb-1.2.1&auto=format&fit=crop&w=2202&q=80"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-3 white--text"
            style="height: 100%; opacity: 60%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <font size="12"><b>DESSERTS</b></font>
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