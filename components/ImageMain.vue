<template>
  
  <v-container fluid>
  <!--Intially used cards for images then used for loop>
  <!-- used justify for contibuting to make the image responsive cause when the margins were defined, the images had a lot of space between them.
  For the overlay added an average rating so that the users could decide if they want to go ahead with their selection. -->
    <v-row
    justify="center"
      class="mx-auto my-1"
       >
      <v-col
        v-for="card in cards"
        :key="card.title"
        :cols="12" lg="3" md="4" sm="6" xs="12"
        justify="center"
        align="center"
       class="mx-center-auto my-auto"
        
       >
        <v-card>
         
          <v-hover v-slot:default="{ hover }">
          
    <v-card
      
      color="#FFFFFF"
      
      height="352px"
      
      aspect-ratio="16/9"
      class="white--text my-10 rounded-0"
            
    >
      <v-img
      :src="card.src"
      height="350px"
      aspect-ratio="16/9">
        <v-expand-transition>
          <div
            v-if="hover"
            
            class="d-flex transition-fast-in-fast-out black lighten-2 v-card--reveal display-4 white--text"
            style="height: 100%; opacity: 70%; text-opacity: 100%;"
            >
            <div class="align-self-center">
            <v-flex class="mx-5"> 
           <v-card-title  v-text="card.title" class="text-h4 font-weight-medium font-family-Calibri"></v-card-title>
            <div class="align-self-center">
            <v-rating
  color="#C0C0C0"
  half-increments
  length="5"
  size="30"
  value="4"
></v-rating>
   </div>        
    
           </v-flex>
           </div>

          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-10"
        style="position: relative;"
      >
       
      </v-card-text>
    </v-card>
  </v-hover>
            
          </v-img>
          

            
         </v-card>
       </v-col>
    </v-row>
  </v-container>
  
</template>

<v-divider inset color="black" width="2000"></v-divider>

<script>
  export default {
    data: () => ({
      cards: [
        { title: 'INDIAN THALI', src: 'https://curlytales.com/wp-content/uploads/2017/07/thali-food-india-e1500888181584-1280x720.jpg', value:'4', },
        { title: 'CONTINENTAL', src: 'https://images.unsplash.com/photo-1546453570-d2fcacdafbb2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjF9&auto=format&fit=crop&w=3135&q=80', value:'5', },
        { title: 'FIT & FAB', src: 'https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=3150&q=80' ,value:'4',},
        { title: 'WOK STATION', src: 'https://images.unsplash.com/photo-1509680859026-7d8cfc6894f4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80' , value:'4',},
        { title: 'BIG BIRYANI', src: 'https://images.unsplash.com/photo-1552590635-27c2c2128abf?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80'  ,value:'5',},
        { title: 'PIZZAS', src: 'https://images.unsplash.com/photo-1574126154517-d1e0d89ef734?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1934&q=80', value:'4', },
        { title: 'SNACKS', src: 'https://images.unsplash.com/photo-1586838488967-8ba28530505f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80', value:'5', },
        { title: 'BEVERAGE', src: 'https://images.unsplash.com/photo-1551024709-8f23befc6f87?ixlib=rb-1.2.1&auto=format&fit=crop&w=2850&q=80' ,value:'4',},
        { title: 'DESSERT', src: 'https://images.unsplash.com/photo-1562634335-2f6a3668319d?ixlib=rb-1.2.1&auto=format&fit=crop&w=2202&q=80' , value:'5',},
        
      ],
    }),
  }
</script>
