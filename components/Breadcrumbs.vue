<template>
  <div>
    <v-breadcrumbs :items="items">
      <template v-slot:divider>
        <v-icon>mdi-forward</v-icon>
      </template>
    </v-breadcrumbs>

   
  </div>
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'HOME',
          disabled: false,
          href: 'breadcrumbs_dashboard',
        },
        {
          text: 'PREVIEW',
          disabled: false,
          href: 'PREVIEW',
        },
        {
          text: 'Link 2',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
      ],
    }),
  }
</script>