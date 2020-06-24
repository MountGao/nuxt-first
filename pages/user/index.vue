<template>
    <div>
      <h1>user/index</h1>
    </div>
</template>

<script>
    export default {
        name: "index",

        mixins: [],

        components: {},

        props: {},

        data() {
            return {}
        },

        computed: {},

        watch: {},

        created() {
            console.log('created')
        },

        mounted() {
        },

        destroyed() {
        },

        methods: {},

        middleware: 'user',

        head: {
            title: 'user-index',
            meta: [
                { hid: 'description', name: 'description', content: 'user description' },
                { hid: 'og:description', property: 'og:description', content: 'user og:description' }
            ],
        }

    }
</script>

<style scoped>

</style>
