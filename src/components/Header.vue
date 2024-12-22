<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
    <header>
        <h1>JIMMY</h1>
        <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        </nav>
    </header>
</template>

<style>

header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    color: white;
    text-align: center;
}

nav {
    display: flex;
    gap: 1rem;
}

</style>
