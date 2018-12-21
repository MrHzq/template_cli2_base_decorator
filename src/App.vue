<template>
    <div id="app">
        <router-view />
    </div>
</template>

<script>
    import { Vue, Component, Prop } from 'vue-property-decorator'
    @Component
    export default class App extends Vue {}
</script>
<style>
    @import './style/app.scss';
</style>
