<template>
    <div class="contents">
        <span>{{ msg }}</span>
        <h1>{{ input }}</h1>
    </div>
</template>

<script>
    export default {
        name: 'about',
        props: ['input'],
        data () {
            return {
                msg: 'We are awesome company of enthusiasts, which aim is to make our world a better place!'
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .contents {
        font-weight: bold;
    }
</style>
