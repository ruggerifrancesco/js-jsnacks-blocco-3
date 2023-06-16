<template>
    <li>{{ itemName }}</li>
</template>

<script>
export default {
  props: {
    itemName: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
    
</style>