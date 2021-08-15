<template>
    <main>
        <Header />
        <section class="login">
            <div class="login__form">
                <LoginForm />
            </div>
        </section>
    </main>
</template>

<script>
import Header from '@/components/common/Header/Header'
import LoginForm from '@/components/Login/login-form'

export default {
    name: 'Login',
    components: { Header, LoginForm },
}
</script>

<style lang="scss" scoped>
.login {
    padding: 95px 0 0;
    min-height: 100vh;

    &__form {
        margin: 0 auto;
        width: 100%;
        max-width: 400px;
    }
}
</style>
