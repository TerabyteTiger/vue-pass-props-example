<template>
  <grandchild :passedFromParent="passedFromParent"/>
</template>

<script>
import grandchild from './grandchild.vue'
export default {
  name: "parent",
  props: {
    passedFromParent: Number
  },
  components: {
    grandchild
  }
}
</script>
