<template>
  <ons-list-item v-on="unrecognizedListeners" :modifier="normalizedModifier">
    <slot></slot>
  </ons-list-item>
</template>

<script>
  /* This file was generated automatically by 'generate-components' task in bindings/vue/gulpfile.babel.js */
  import 'onsenui/esm/elements/ons-list-item';
  import { deriveEvents, modifier } from '../mixins';

  export default {
    name: 'v-ons-list-item',
    mixins: [deriveEvents, modifier]
  };
</script>