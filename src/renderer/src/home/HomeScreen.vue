<script lang="ts" setup>
const startListen = () => {
  alert('Start Listening...')
}
const stopListening = () => {
  alert('Stop Listening!')
}
</script>
<template>
  <div>
    <button @click="startListen">Listen</button>
    <button
      @click="stopListening">Stop Listen</button>
  </div>
</template>
