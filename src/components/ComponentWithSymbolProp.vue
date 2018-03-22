<template>
  <div class="hello">
   component
  </div>
</template>

<script>
export default {
  name: 'ComponentWithSymbolProp',
  props: {
    symbolProp: {
      type: Symbol,
      required: true,
    },
  },
};
</script>
