<template>
    <div class="  bg-green-500 ">
        <div class="w-11/12 mx-auto flex justify-between items-center py-2 ">
            <!-- logo section -->
            <div>
                <img class="w-12 h-12" :src="logo" alt="logo">
            </div>
            <!-- nav items -->
            <div class=" flex justify-center gap-3">
                <div v-for="link in links" :key="link">
                    <a class="font-semibold text-xl text-white hover:text-gray-300" href="">{{ link }}</a>
                </div>
            </div>
            <div>
                <a class="font-semibold text-xl text-white" href="">Login</a>
            </div>
        </div>

    </div>


</template>







<script setup>
import logo from '../assets/logo.png'

const links = ['About', 'Jobs', 'Add Jobs']
</script>

<style></style>