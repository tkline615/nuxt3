<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/">Nuxt Dojo</NuxtLink>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum aut culpa maiores modi ad nihil beatae ut commodi labore deleniti.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum aut culpa maiores modi ad nihil beatae ut commodi labore deleniti.</p>
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
    }
</style>