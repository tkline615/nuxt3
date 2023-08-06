<template>
    <div>
        <p>Products details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat provident obcaecati iusto quisquam sequi quasi hic eum, nostrum neque cumque?</p>
    </div>
</template>

<script setup>
    // this name must match the [id] value
    const { id } = useRoute().params
</script>

<style scoped>

</style>