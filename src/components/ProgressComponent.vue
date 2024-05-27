<template>
    <div class="relative h-1.5 bg-neutral-400 w-3/4">
        <div :style="{ width: props.width + '%' }" class="absolute h-1.5 bg-neutral-700"></div>
    </div>
</template>
<script setup>
const props = defineProps({
    width: {
        type: [Number, null],
        required: false,
        default: 100
    }
})
</script>
