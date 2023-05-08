<template>
    <h1>
        {{ props.title }}
    </h1>
    
</template>


<script setup>
const { twitterBorderColor, defaultTransition } = useTailwindConfig()

const props = defineProps({
    title: {
        type: String,
        required: true
    }
})

</script>