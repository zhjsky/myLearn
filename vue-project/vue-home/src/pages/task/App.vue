<template>
    <div id="app">
        <div id="nav">
            <router-link to="/">Task</router-link> |
            <router-link to="/sign">Sign</router-link>
        </div>
        <router-view/>
    </div>
</template>
<style lang="stylus">
#app
    font-family 'Avenir', Helvetica, Arial, sans-serif
    -webkit-font-smoothing antialiased
    -moz-osx-font-smoothing grayscale
    text-align center
    color #2c3e50
    font-size: 32px;

#nav
    padding 30px
    a
        font-weight bold
        color #2c3e50
        &.router-link-exact-active
            color #42b983
</style>
