<script setup>
const router = useRouter();
</script>

<template>
    <div class="logo" @click="router.push('/')">
        <h1 class="font-black text-2xl text-slate-900 dark:text-zinc-100">Singlepage</h1>
        <h2 class="text-sm text-slate-900/50 dark:text-zinc-100">Development</h2>
    </div>
</template>

<style>
.logo{
    @apply cursor-pointer flex flex-col;
}
</style>