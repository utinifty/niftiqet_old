<template>
  <div class="event--card-grid" :class="gridSize === 3 ? 'three' : 'two'">
    <event-card :self="linkSelf" />
    <event-card :self="linkSelf" />
    <event-card :self="linkSelf" />
    <event-card :self="linkSelf" />
    <event-card :self="linkSelf" />
    <event-card :self="linkSelf" />
  </div>
</template>

<script>
export default {
  props: {
    gridSize: {
      type: Number,
      default(){
        return 3
      }
    },
    linkSelf: {
      type: Boolean,
      default(){
        return false
      }
    }
  }
}

</script>

<style scoped>

</style>
