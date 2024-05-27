<template>
    <div>
        <h1 class="font-bold text-xl uppercase tracking-widest">Languages</h1>
        <div class="mt-2 w-8 h-1 bg-neutral-900 mb-4" />
        <div class="space-y-4">
            <div class="space-y-1">
                <h1 class="">Dutch</h1>
                <ProgressComponent :width="100"></ProgressComponent>
            </div>
            <div class="space-y-1">
                <h1 class="">English</h1>
                <ProgressComponent :width="100"></ProgressComponent>
            </div>
            <div class="space-y-1">
                <h1 class="">German</h1>
                <ProgressComponent :width="35"></ProgressComponent>
            </div>
        </div>
    </div>
</template>
<script setup>
import ProgressComponent from '@/components/ProgressComponent.vue'
</script>
