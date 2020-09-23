<template>
<template>
  
  <v-container fluid>
    <v-row justify="center"
      class="mx-auto">
      <v-col
        v-for="card in cards"
        :key="card.title"
        :cols="12" lg="4" md="4" sm="6" 
       >
        <v-card>
          <v-img
            :src="card.src"
            class="white--text"
            blur
            height="200px"
          >
            <v-card-title  v-text="card.title" class="text-h5 font-weight-medium"></v-card-title>
          </v-img>

            
         </v-card>





<v-hover v-slot:default="{ hover }">
    <v-card
      class="mb-16"
      color=""
      max-width="500"
      max-height="2"
    >
      <v-img
        :src="card.src"
            class="white--text"
            blur
            height="200px"
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
    </v-row>

  </v-container>
  
</template>

<script>
  export default {
    data: () => ({
      cards: [
        { title: 'INDIAN THALI', src: 'https://curlytales.com/wp-content/uploads/2017/07/thali-food-india-e1500888181584-1280x720.jpg' },
        { title: 'CONTINENTAL', src: 'https://im.whatshot.in/content/2016/Sep/1473757744-forresta-rev.jpg' },
        { title: 'FIT & FAB', src: 'Fit.jpg'},
        { title: 'WOK STATION', src: 'https://images.unsplash.com/photo-1509680859026-7d8cfc6894f4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80' },
        { title: 'BIG BIRYANI CO.', src: 'https://images.unsplash.com/photo-1552590635-27c2c2128abf?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80' },
        { title: 'PIZZAS', sr: 'https://images.unsplash.com/photo-1574126154517-d1e0d89ef734?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1934&q=80',  },
        { title: 'SNACKS', src: 'https://images.unsplash.com/photo-1586838488967-8ba28530505f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2250&q=80' },
        { title: 'BEVERAGE', src: 'https://images.unsplash.com/photo-1551024709-8f23befc6f87?ixlib=rb-1.2.1&auto=format&fit=crop&w=2850&q=80'},
        { title: 'DESSERT', src: 'https://images.unsplash.com/photo-1562634335-2f6a3668319d?ixlib=rb-1.2.1&auto=format&fit=crop&w=2202&q=80' },
        
      ],
    }),
  }
</script>

  </v-container>
</template>