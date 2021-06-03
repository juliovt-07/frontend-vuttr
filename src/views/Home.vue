<template>
  <div class="card card-elevation-1 b-darker-white">
    <h1 class="header-1 left dark-purple">VUTTR</h1>
    <h3 class="header-5 left dark-purple">Very Userfull Tools to Remember</h3>
    <div class="actions">
      <input class="bg-darkest-white dark-purple" placeholder="Search" type="text">
      <button class="btn bg-dark-purple white"><img src="../assets/icons/icon-plus-circle.svg" width="18"> Add</button>
    </div>
    <div class="card-list">
      <div class="card card-elevation-2">
        <div class="body">
          <p class="dark-purple">title</p>
          <a href="#" class="body-smallest ink">remove</a>
        </div>
        <div class="body-smallest left">description Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
        <div class="body-smallest left tags">#title</div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home'
}
</script>

<style scoped lang="sass">
.left
  text-align: left
.right
  text-align: right
.actions
  margin: 20px 0 20px 0
  display: grid
  grid-template-columns: auto auto
  grid-column-gap: 15px
  justify-content: space-between
  input
    border: none
    padding: 5px
    border-radius: 5px
    outline: none
    font-size: 16px
  button
    display: grid
    grid-template-columns: auto auto
    grid-column-gap: 10px
    justify-content: center
.card-list
  .card
    display: grid
    grid-gap: 5px
  .body
    display: grid
    grid-template-columns: auto auto
    justify-content: space-between
    p
      text-decoration: underline
    a
      text-decoration: none
      font-weight: bold
  .tags
    font-weight: bold
</style>
