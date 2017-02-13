<template>
    <header>
        <div class="title">
            <span>{{ title }}</span>
        </div>
        <div class="navigation">
            <nav>
                <a v-for="link of navigation" :href="link.route">{{ link.text }}</a>
            </nav>
        </div>
    </header>
</template>

<script>
    export default {
        name: 'app-header',
        data () {
            return {
                title: 'Architech',
                navigation: [
                    {
                        text: 'About',
                        route: '/about'
                    },
                    {
                        text: 'Pricing',
                        route: '/pricing'
                    }
                ]
            }
        }
    }
</script>

<style src="../assets/styles/app-header.less" lang="less" scoped></style>
