<template>
<nav>
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

<slot/>
</template>

<script>

</script>

<style>

</style>