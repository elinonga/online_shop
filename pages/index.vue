<template>
    <div>

        <header>
            <nav>
                <NuxtLink to="/">Kwanza App</NuxtLink>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <h2>Home</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
            ultricies, nisl nec ultricies lacinia, nunc nisl aliquet nisl, a
            tincidunt nisl nisl sit amet nisl.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
            ultricies, nisl nec ultricies lacinia, nunc nisl aliquet nisl, a
            tincidunt nisl nisl sit amet nisl.</p>
    </div>
</template>

<script setup>

</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }
    p {
        margin: 20px 0;
        font-size: 18px;
    }
</style>