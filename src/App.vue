<template>
  <div id="nav">
  </div>
  <router-view/>
</template>

<style lang="sass">
@import "styles/normalize"
@import "styles/reset"
@import "styles/variables/iconography"
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;600&display=swap')
@import "styles/variables/colors"
@import "styles/variables/typography"

.icon-cancel-circle
  background: url($cancel-circle) no-repeat
.icon-close
  background: url($close) no-repeat
.icon-learn
  background: url($learn) no-repeat
.icon-pin
  background: url($pin) no-repeat
.icon-plus-circle
  background: url($plus-circle) no-repeat
.icon-search
  background: url($search) no-repeat
#app
  font-family: 'Source Sans Pro', sans-serif
  background: $white
  text-align: center
  color: #2c3e50
  padding: 20px 100px

#nav
  padding: 30px
  a
    font-weight: bold
    color: #2c3e50

    &.router-link-exact-active
      color: #42b983
</style>
