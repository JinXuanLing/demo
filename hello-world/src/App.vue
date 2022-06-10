<template>
    <div id="app">
        <i-button>按钮</i-button>
    </div>
</template>

<script>
import IButton from './components/button/i-button.vue';

export default {
    name: 'App',
    components: {
        IButton,
    },
};
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
</style>
