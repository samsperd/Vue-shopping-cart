<template>
  <v-item-group>
    <v-container>
        <p>
          Welcome to my Vue Shopping Cart
        </p>

        <product />
    </v-container>
  </v-item-group>
  </template>

<script>
  export default {
    name: 'HelloWorld',
    data: () => ({
cards: [
        { title: 'Pre-fab homes', src: 'https://cdn.vuetifyjs.com/images/cards/house.jpg', flex: 3 },
        { title: 'Favorite road trips', src: 'https://cdn.vuetifyjs.com/images/cards/road.jpg', flex: 3 },
        { title: 'Best airlines', src: 'https://cdn.vuetifyjs.com/images/cards/plane.jpg', flex: 3 },
      ],
    }),
  }
</script>
