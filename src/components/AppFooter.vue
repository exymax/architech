<template>
    <footer>
        <div class="copyright">{{ copyright }}</div>
        <div class="developer-message">
            <span>{{ developerMessage }}</span>
        </div>
    </footer>
</template>

<script>
    export default {
        name: 'app-footer',
        data () {
            return {
                copyright: 'Architech©2017',
                developerMessage: 'Crafted with luv by exymax'
            }
        }
    }
</script>

<style src="../assets/styles/app-footer.less" lang="less" scoped></style>
