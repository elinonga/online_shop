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

        <!-- Output page content -->
        <div>
            <slot />
        </div>

    </div>
</template>

<style scoped>
    .router-link-exact-active {
        color: #42b983;
    }
</style>
