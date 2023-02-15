<script lang="ts" setup>
import { ethers } from "ethers";
const wave = () => {

}

</script>

<template>
    <div class="h-screen w-screen flex bg-neutral-100 justify-center items-center">
        <div class="flex flex-col space-y-6 p-5 border border-gray-400 rounded-lg bg-neutral-300 ">
            <h1 class="text-3xl text-center text-gray-700">👋 Hello from WavePortal</h1>
            <p class="text-center text-gray-700">Hi! I'm raudmees and I am freelancer programmer and cybersecurity student. Connect your Ethereum wallet and wave at me!</p>
            <button class="btn btn-info w-full" @click="wave">Wave me</button>
        </div>
    </div>
</template>