<script setup lang="js">
// import { useSlots, useAttrs } from 'vue';

// const slots = useSlots();
// const attrs = useAttrs();

const props = defineProps({
    src: {
        type: String,
    },
    title: {
        type: String,
    },
});

</script>

<template>
<iframe
    width="100%"
    height="100%"
    style="width: 100%; height: 100vh;"
    :src="src"
    :title="title"
    frameborder="0"
    referrerpolicy="no-referrer-when-cross-origin"
    allowfullscreen
></iframe>
</template>
