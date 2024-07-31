<template>
  <div :class="`${bg}`">
    <slot></slot>
  </div>
</template>

<script setup>
import {defineProps} from 'vue';
defineProps({
    bg:{
        type: String,
        default: 'bg-gray-100'
    }
})
</script>

<style>

</style>