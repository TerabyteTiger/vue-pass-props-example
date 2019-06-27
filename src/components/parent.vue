<template>
  <child :passedFromParent="passMe"/>
</template>

<script>
import child from "./child.vue"
export default {
  name: "parent",
  data(){
    return{
      passMe: 5
    }
  },
  components: {
    child
  }
}
</script>
