<template>
<div class="h-52 bg-green-400 text-white text-center ">
    <h1 class="font-extrabold text-4xl pt-12 ">{{ title }}</h1>
    <p class="text-xl mt-3">{{ subTitle }}</p>
</div>
</template>

<script setup>
import {defineProps} from 'vue';


defineProps({
title:{
    type: String,
    default: 'Become a Vue Dev'
},
subTitle:{
    type: String,
    default: 'Find the vue jobs that finds your skills and needs'
}
});

</script>

<style>

</style>