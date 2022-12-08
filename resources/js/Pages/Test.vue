<script setup>
import { ref } from "vue"

const number  = ref(0)
</script>

<template>
    <h1>Vue test</h1>
    <div class="bg-gray-500">number is: {{ number }}</div>
    <button @click="number++">Update</button>

</template>
