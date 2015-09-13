<template lang="jade">
    div.header
        div.nav
            ul.top-bar
                li 首页
                li 动态
                li 看板
                li 简报
                li 团队
            div.right-bar
                p 团队协作工具
</template>

<style lang="stylus">
    .header
        height: 45px
        width: 100%
        border-bottom: 1px solid #ddd
    
    .nav
        display: flex
        flex-direction: row
        justify-content:  space-between
        width: 960px
        margin:0 auto;

    .top-bar
        display: flex
        flex-direction: row
        margin: 0 auto
        text-align: center

    .top-bar
        li
            line-height: 45px
            width: 54px
            list-style: none
</style>