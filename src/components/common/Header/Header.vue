<template>
    <header :class="styles.header">
        <h3>There is HEADER</h3>
    </header>
</template>

<script>
// eslint-disable-next-line
import styles from './header.module.scss'

export default {
    name: 'Header',
    data() {
        return {
            styles,
        }
    },
}
</script>
