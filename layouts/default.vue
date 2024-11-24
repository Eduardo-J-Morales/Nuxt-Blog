<template>
<<<<<<< HEAD
=======
<nav>
>>>>>>> 0449994c77f8441b5940057ba1276dd00c98f153
    <div>
        <header>
            <nav>
                <div>
                    <div>
                        <NuxtLink>
<<<<<<< HEAD
=======

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
                            <template>
                                <NuxtLink>Login</NuxtLink>
                            </template>
                            <template>
                                <button @click="logout"></button>
                            </template>
                        </ClientOnly>
                    </div>
                </div>
            </nav>
        </header>
    </div>
</nav>
>>>>>>> 0449994c77f8441b5940057ba1276dd00c98f153

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