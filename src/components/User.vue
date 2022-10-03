<template>
    <div>
        <b-table striped hover :items="players"></b-table>
    </div>
</template>
<script>
    export default {
        props: {
            players: {
                type: Array,
                required: true
            }
        }
    }
</script>