<template>
    <div id="app">
        {{ message }}
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
let app = new Vue({
    el: '#app',
    data: {
        message: 'Primeiro teste em Vue!'
    }
})
</script>

<style lang="stylus">

</style>