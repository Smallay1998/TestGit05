<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4">
                <NuxtLink to="/products" class="font-bold">Archons</NuxtLink>
            </nav>
        </header>

        <!-- page content go here -->
        <div class="container mx-auto p-4">
            <slot />
        </div>

        <footer class="container mx-auto p-4 flex justify-between border-t-2">
            <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/Barbatos" class="btn">Barbatos</NuxtLink></li>
                    <li><NuxtLink to="/Beelzebun" class="btn">Beelzebun</NuxtLink></li>
                    <li><NuxtLink to="/Buer" class="btn">Buer</NuxtLink></li>
                    <li><NuxtLink to="/Morax" class="btn">Morax</NuxtLink></li>
            </ul>
        </footer>
    </div>
</template>

<style scoped>
    .router-link-exact-active {
        color: #FFd800;
    }
</style>