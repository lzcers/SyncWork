<template lang="jade">
    div.container
        header
            nav
        main
            progress
</template>

<style lang="stylus">
    html, body
        margin: 0 0
        padding: 0 0
        border: 0
        font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        font-size: 14px

    .container
        width: 960px
        margin: 0 auto

    header
        height: 45px
        width: 100%
        border-bottom: 1px solid #ddd

    main
        margin-top: 10px

</style>

<script type="babel">
    import nav from './components/nav.vue';
    import progress from './components/progress.vue';
    import timeline from './components/timeline.vue';
    export default {
        data() {
            return {title: "hello world"};
        },
        components: {
            'nav': nav,
            'progress': progress,
            // 'timeline': timeline
        }
    };
</script>