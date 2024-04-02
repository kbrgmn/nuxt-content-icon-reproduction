<template>
    <div>
        <p>Different component here</p>
        <div>
            <slot/>
        </div>
    </div>
</template>

<script lang="ts" setup>
defineProps({
    imgWidth: {
        type: [String, Number],
        default: undefined,
    },
});
</script>
