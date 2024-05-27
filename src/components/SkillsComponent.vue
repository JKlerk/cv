<template>
    <div>
        <h1 class="font-bold text-xl uppercase tracking-widest">Skills</h1>
        <div class="mt-2 w-8 h-1 bg-neutral-900 mb-4" />
        <div class="space-y-4">
            <div class="space-y-1">
                <h1 class="">JavaScript / Typescript</h1>
                <ProgressComponent :width="100"></ProgressComponent>
            </div>
            <div class="space-y-1">
                <h1 class="">Vue.js</h1>
                <ProgressComponent :width="100"></ProgressComponent>
            </div>
            <div class="space-y-1">
                <h1 class="">HTML / CSS</h1>
                <ProgressComponent :width="90"></ProgressComponent>
            </div>
            <div class="space-y-1">
                <h1 class="">PHP / Laravel</h1>
                <ProgressComponent :width="65"></ProgressComponent>
            </div>
            <div class="space-y-1">
                <h1 class="">SQL</h1>
                <ProgressComponent :width="60"></ProgressComponent>
            </div>
            <div class="space-y-1">
                <h1 class="">C# / Java</h1>
                <ProgressComponent :width="75"></ProgressComponent>
            </div>
        </div>
    </div>
</template>
<script setup>
import ProgressComponent from '@/components/ProgressComponent.vue'
</script>
