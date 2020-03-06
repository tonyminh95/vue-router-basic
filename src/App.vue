<template>
    <div id="app">
        <div id="nav">
            <router-link to="/">Home</router-link>
            <router-link to="/brazil">Brazil</router-link>
            <router-link to="/jamaica">Jamaica</router-link>
            <router-link to="/hawaii">Hawaii</router-link>
            <router-link to="/panama">Panama</router-link>
        </div>
        <router-view/>
    </div>
</template>

<script>
    export default {
        name: 'App',
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }

    #nav a:not(:last-child) {
        margin-right: 10px;
    }
</style>
