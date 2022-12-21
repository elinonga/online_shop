<template>
    <div>

        <h2>Product number for {{ $route.params.id }}</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
            ultricies, nisl nec ultricies lacinia, nunc nisl aliquet nisl, a
            tincidunt nisl nisl sit amet nisl?</p>

    </div>
</template>

<script setup>
    const { params } = useRoute().params;
</script>

<style scoped>

</style>