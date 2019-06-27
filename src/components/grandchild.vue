<template>
  <div>
    {{passedFromParent}}
  </div>
</template>

<script>
export default {
  name: "grandchild",
  props: {
    passedFromParent: Number
  }
}
</script>
