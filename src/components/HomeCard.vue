<template>
    <div class="flex flex-col lg:flex-row gap-16 justify-center items-center mt-12 w-11/12 mx-auto">
        <Card class="bg-gray-100 rounded-md shadow-md p-6">
            <h3 class="text-2xl font-bold">For Developers</h3>
            <p class="mt-2 mb-4">Browse our view jobs and start your career today.</p>
            <button class="inline-block bg-black text-white rounded-md px-4 py-2 hover:bg-gray-700">Browse Jobs</button>
        </Card>

        <Card bg="bg-green-100" class="rounded-md shadow-md p-6">
            <h3 class="text-2xl font-bold">For Employers</h3>
            <p class="mt-2 mb-4">Browse our view jobs and start your career today.</p>
            <button  class="inline-block bg-green-500 text-white rounded-md px-4 py-2 hover:bg-green-600">Browse Jobs</button>
        </Card>
    </div>
</template>

<script setup>
import Card from './Card.vue'
</script>

<style></style>