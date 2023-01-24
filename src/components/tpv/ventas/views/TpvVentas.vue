<template>
  <h3>Hola</h3>
</template>
<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'TpvVentas',
  props: {
    title: {
      type: String,
      required: true,
    },

    caption: {
      type: String,
      default: '',
    },

    link: {
      type: String,
      default: '#',
    },

    icon: {
      type: String,
      default: '',
    },
  },
});
</script>
