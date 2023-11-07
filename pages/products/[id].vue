<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorum deleniti tempore voluptas debitis sunt
            accusantium ipsa hic tempora placeat aut.</p>
    </div>
</template>

<script setup>
definePageMeta({
    layout: 'products',
})
const { id } = useRoute().params
</script>

<style scoped></style>