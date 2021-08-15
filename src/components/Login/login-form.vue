<template>
    <form :class="styles['login-form']" action="#">
        <div :class="styles['header']">
            <p :class="styles['header__text']">Login</p>
        </div>
        <div :class="styles['input-wrapper']">
            <v-text-field label="Login" outlined loading="true"></v-text-field>
        </div>
        <div :class="styles['input-wrapper']"></div>
    </form>
</template>

<script>
import styles from './login-form.module.scss'

export default {
    name: 'LoginForm',

    data() {
        return {
            styles,
        }
    },
}
</script>
