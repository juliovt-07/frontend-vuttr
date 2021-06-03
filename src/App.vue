<template>
  <div id="nav">
  </div>
  <router-view class="content"/>
</template>

<style lang="sass">
@import "styles/styles"

body
  background: $darkerWhite
#app
  font-family: 'Source Sans Pro', sans-serif
  text-align: center
  color: #2c3e50
  padding: 50px 20%

#nav
  padding: 30px
  a
    font-weight: bold
    color: #2c3e50

    &.router-link-exact-active
      color: #42b983
.content
  max-width: 50vw
.btn
  min-width: 114px
  max-width: 150px
  min-height: 25px
  padding: 5px
  border: none
  border-radius: 5px
  box-shadow: 0px 10px 10px #0000000D
  cursor: pointer
</style>
