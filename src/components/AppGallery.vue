<template>
    <main>
        <div class="gallery-item" v-for="item of items">
            <img :src="item.image">
            <div class="title">{{ item.title }}</div>
            <div class="description">{{ item.description }}</div>
        </div>
    </main>
</template>

<script>
    export default {
        name: 'app-gallery',
        data () {
            return {
                items: [
                    {
                        image: 'http://lorempixel.com/400/200/nature',
                        title: 'Title 1',
                        description: 'Lorem ipsum dolor sit amet! Lorem ipsum dolor sit amet!'
                    },
                    {
                        image: 'http://lorempixel.com/400/200/nature',
                        title: 'Title 2',
                        description: 'Lorem ipsum dolor sit amet! Lorem ipsum dolor sit amet!'
                    },
                    {
                        image: 'http://lorempixel.com/400/200/nature',
                        title: 'Title 3',
                        description: 'Lorem ipsum dolor sit amet! Lorem ipsum dolor sit amet!'
                    },
                    {
                        image: 'http://lorempixel.com/400/200/nature',
                        title: 'Title 4',
                        description: 'Lorem ipsum dolor sit amet! Lorem ipsum dolor sit amet!'
                    },
                    {
                        image: 'http://lorempixel.com/400/200/nature',
                        title: 'Title 5',
                        description: 'Lorem ipsum dolor sit amet! Lorem ipsum dolor sit amet!'
                    }
                ]
            }
        }
    }
</script>

<style src="../assets/styles/app-gallery.less" lang="less" scoped></style>
