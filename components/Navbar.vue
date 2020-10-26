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
      <template v-slot:img="{ props }">
        <v-img
          v-bind="props"
          style="height: 100%; opacity: 32%; text-opacity: 100%"
          
        ></v-img>
      </template>

      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon medium>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-card-text><h3>HELP</h3></v-card-text>
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
            <v-icon medium>mdi-cart</v-icon>
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

      <template v-slot:extension>
        <v-tabs align-bottom>
          <v-tab class="mx-14">SIGNUP</v-tab>
          <v-tab class="mr-10">LOGIN</v-tab>
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
