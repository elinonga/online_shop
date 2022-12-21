<template>
    <div>

        <header>
            <nav>
                <NuxtLink to="/products">Kwanza App Products</NuxtLink>
            </nav>
        </header>

        <!-- Output page content -->
        <div>
            <slot />
        </div>

        <footer>
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/products">Products</NuxtLink></li>
            </ul>
        </footer>

    </div>
</template>

<style scoped>
    .router-link-exact-active {
        color: #42b983;
    }
</style>
