<template>
  <v-card
    class="mx-auto"
    max-width="1300"
  >
    <v-system-bar
      color="indigo darken-2"
      dark
    >
      <v-spacer></v-spacer>

      <v-icon>mdi-window-minimize</v-icon>

      <v-icon>mdi-window-maximize</v-icon>

      <v-icon>mdi-close</v-icon>
    </v-system-bar>

    <v-toolbar
      color="indigo"
      dark
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Discover</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
    </v-toolbar>

    <v-container fluid>
      <v-row dense>
        <v-col
          v-for="card in cards"
          :key="card.title"
          :cols="card.flex"
        >
          <v-card>
            <v-img
              :src="card.src"
              class="white--text align-top"
              gradient="to top, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="490px"
            >
              <v-card-title v-text="card.title"></v-card-title>
            </v-img>

            <v-card-actions>
              <v-spacer></v-spacer>

              <v-btn icon>
                <v-icon color="yellow">mdi-bookmark</v-icon>
              </v-btn>

              <v-btn icon>
                <v-icon color="pink">mdi-heart</v-icon>
              </v-btn>

              <v-btn icon>
                <v-icon color="blue">mdi-share-variant</v-icon>
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-card>
</template>

<script>
  export default {
    data: () => ({
      cards: [
        { title: 'Pre-fab homes', src: 'Indian.jpg', flex: 12 },
        { title: 'Favorite road trips', src: 'Fit.jpeg', flex: 6 },
        { title: 'Best airlines', src: 'Indian.jpg', flex: 6 },
        { title: 'Trial', src: 'https://cdn.vuetifyjs.com/images/cards/plane.jpg', flex: 12 },
        { title: 'Flex 8', src: 'https://cdn.vuetifyjs.com/images/cards/house.jpg', flex: 3 },
        { title: 'Flex 4', src: 'https://cdn.vuetifyjs.com/images/cards/road.jpg', flex: 6 },
        { title: 'Flex 4', src: 'https://cdn.vuetifyjs.com/images/cards/road.jpg', flex: 3 },
      ],
    }),
  }
</script>