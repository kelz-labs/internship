<script>
export default {
  name: 'HomeComponent',
  props: { name: { type: String } },
  data() {
    return {
      drinks: [
        { name: 'Anime kan bang', price: '$3.00' },
        { name: 'Soda', price: '$2.50' }
      ]
    }
  }
}
</script>
<template>
  <p>{{ name }}</p>
</template>
