<template>
    <div>
      <b-navbar type="dark" variant="dark">
      <b-navbar-nav>
      <b-nav-item href="#">Главная</b-nav-item>

      <b-nav-item-dropdown text="Меню" right>
        <b-dropdown-item href="#">Профиль</b-dropdown-item>
        <b-dropdown-item href="#">Настройки</b-dropdown-item>
      </b-nav-item-dropdown>  
      </b-navbar-nav>
      </b-navbar>
    </div>
</template>

<script>
    import 'bootstrap/dist/css/bootstrap.css'
    import 'bootstrap-vue/dist/bootstrap-vue.css'

    export default {
        data() {
            return {

            }
        }
    }
</script>

<style>
</style>
