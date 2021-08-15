<template>
    <div id="app">
        <Login />
    </div>
</template>

<script>
import Login from '@/views/Login'

export default {
    name: 'App',
    components: {
        Login,
    },
}
</script>

<style lang="scss">
// eslint-disable-next-line

#app {
    width: 100%;
}
</style>
