<template lang="jade">
    nav
</template>

<script type="babel">
    import nav from './components/nav.vue';
    export default {
        data() {
            return {title : "hello world"};
        },
        components: {
            'nav' : nav
        }
    };
</script>