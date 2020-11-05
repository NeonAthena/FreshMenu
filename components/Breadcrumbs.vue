<template>
  <div>
    <v-breadcrumbs :items="items" class="my-10 mx-6">
      <template v-slot:divider>
        <v-icon color="grey">mdi-greater-than</v-icon>
       
      </template>
    </v-breadcrumbs>
    <!-- intially used the HR tag for line then used v-divider to give it a more asthetic feel and just tried writing color="black" and it worked, earlier before the color was specified the line couldnt be seen -->
  <v-divider inset color="black" width="2000"></v-divider>
 <!-- tried adding icon instead of the word home, didnt work out-->
   
  </div>
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'Home',
          disabled: false,
          href: 'breadcrumbs_dashboard',
        },
        {
          text: 'Categories',
          disabled: false,
          href: 'breadcrumbs_link_1',
        },
        
      ],
    }),
  }
</script>