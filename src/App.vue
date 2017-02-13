<template>
    <div id="app">
        <AppHeader />
        <AppGallery />
        <AppFooter />
    </div>
</template>

<script>
    import AppHeader from './components/AppHeader'
    import AppGallery from './components/AppGallery'
    import AppFooter from './components/AppFooter'

    export default {
        name: 'app',
        components: { AppHeader, AppGallery, AppFooter }
    }
</script>

<style src="./assets/styles/app.less" lang="less"></style>
