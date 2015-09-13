<template lang="jade">
    div.container
        header
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
</style>

<script type="babel">
    import header from './components/header.vue';
    export default {
        data() {
            return {title : "hello world"};
        },
        components: {
            'header' : header
        }
    };
</script>