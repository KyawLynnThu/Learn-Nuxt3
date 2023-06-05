<template>
    <div>
        <p>Products details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Saepe soluta, maiores totam vitae nostrum assumenda
            expedita, culpa deserunt cumque, vel eum! Sint quidem ipsam excepturi deleniti quod dolorem aspernatur rem.</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    definePageMeta({
        layout: 'products'
    })
</script>

<style lang="scss" scoped></style>