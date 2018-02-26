<template>
    <div class="container">
        <h1>{{ msg }}</h1>
        <jumbo></jumbo>
    </div>
</template>

<script>
    import Jumbo from './components/jumbo.vue'

    export default {
        data () {
            return {
                msg: 'Hello World'
            }
        },
        components: {
            Jumbo
        }
    }
</script>

<style>

</style>