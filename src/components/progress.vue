<template lang="jade">
    div.progress
        div.pro-up
            div.pro-title
                h1 日乐购商城IT项目
                p 这真是日乐购,此处省略100句内心独白......
                p 协同为目的，而非管理
                p 人有角色，事有所属
            div.pro-status
                div.status-list
                    a.status-item(href="#")
                        span.item-num 12
                        span.item-for 待办事项
                    a.status-item(href="#")
                        span.item-num 12
                        span.item-for 团队成员
                    a.status-item(href="#")
                        span.item-num S
                        span.item-for 设置                        
        div.pro-down
</template>

<style lang="stylus">
    .progress
        width: 960px
        height: 205px
        border: 1px solid #ddd
        padding: 5px
        .pro-up, .pro-down
            display: flex
            flex-direction: row
            justify-content:  space-between
            height: 95px 
            margin-top: 5px
            margin-left: 5px
            margin-right: 5px
        .pro-title,  .pro-status
            h1, p
                margin: 3px 0
            h1
                color: rgb(85, 85, 85);
            p
                color: rgb(136, 136, 119);
    .pro-status
        .status-list
            display: flex
            flex-direction: row
        .status-item
            display: flex
            flex-direction: column 
            width: 70px
            height: 58px
            text-decoration: none
            .item-num
                text-align: center
                font-size: 18px
                line-height: 24px
                color: #06c
            .item-for
                text-align: center
                font-size: 12px
                color: #000
</style>