<template lang="jade">
    div.nav
        div.left-bar
            a#log(href="#") SyncWork
            ul.top-bar
                li: a(href="#") 首页
                li: a(href="#") 动态
                li: a(href="#") 看板
                li: a(href="#") 简报
                li: a(href="#") 团队
        div.right-bar
            p 团队协作工具
</template>

<style lang="stylus">
    .nav
        display: flex
        flex-direction: row
        justify-content:  space-between
        width: 960px
        margin:0 0;
        .left-bar
            display: flex
            flex-direction: row
        .left-bar #log 
            display: block
            line-height: 45px   
            color: rgb(132, 160, 153)
            font-weight: bold
            text-decoration:none

    .top-bar
        display: flex
        flex-direction: row
        margin: 0 0
        padding-left: 0
        text-align: center

    .top-bar
        li
            line-height: 45px
            width: 54px
            list-style: none
        a
            text-decoration: none
            color: #000
</style>