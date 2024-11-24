<template>
    <div>
        <header>
            <nav>
                <div>
                    <div>
                        <NuxtLink>

                            Eduardo Morales - Nuxt Blog
                        </NuxtLink>
                        <div>
                            <NuxtLink>Home</NuxtLink>
                            <NuxtLink>Blog</NuxtLink>
                            <NuxtLink>About</NuxtLink>
                        </div>
                    </div>
                    <div>
                        <ClientOnly>
                            <template >
                                <NuxtLink>Login</NuxtLink>
                            </template>
                            <template>
                                <button @click=""></button>
                            </template>
                        </ClientOnly>
                    </div>
                </div>
            </nav>
        </header>
        <main>
            <slot/>
        </main>
        <footer>
            <div>
                <p>&copy; {{ new Date().getFullYear() }} Eduardo Morales - Nuxt Blog</p>
            </div>
        </footer>
    </div>
</template>

<script setup>

</script>

<style>

</style>