<template>
    <div>
        <h1>Таблица форвардов</h1>
        <my-user :players="players" />
    </div>
</template>

<script>
    import 'bootstrap/dist/css/bootstrap.css'
    import 'bootstrap-vue/dist/bootstrap-vue.css'
    import user from './components/User.vue'

    export default {
        components: {
          'my-user': user
        },
        data() {
            return {
                players: [
                    {number: 29, name: 'Булут', power: 8, speed: 3, dribling: 5, udar: 1, dudar: 2},
                    {number: 25, name: 'Кармазиненко', power: 6, speed: 1, dribling: 6, udar: 4, dudar: 5},
                    {number: 12, name: 'Давтян', power: 3, speed: 1, dribling: 6, udar: 5, dudar: 7},
                    {number: 28, name: 'Вайнбергер', power: 5, speed: 3, dribling: 5, udar: 7, dudar: 6},
                    {number: 27, name: 'Мусона', power: 9, speed: 5, dribling: 5, udar: 3, dudar: 5},
                    {number: 31, name: 'Мойзер', power: 4, speed: 4, dribling: 3, udar: 6, dudar: 5},
                    {number: 13, name: 'Кодзава', power: 5, speed: 5, dribling: 2, udar: 7, dudar: 4},
                    {number: 26, name: 'Булатов', power: 4, speed: 1, dribling: 7, udar: 7, dudar: 6},
                    {number: 10, name: 'Веллинг', power: 9, speed: 1, dribling: 5, udar: 8, dudar: 4},
                    {number: 11, name: 'Алиев', power: 4, speed: 5, dribling: 3, udar: 8, dudar: 4},
                ]
            }
        }
    }
</script>

<style>
</style>
