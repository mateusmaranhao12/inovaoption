<template>
    <div class="container-menor mt-3">
        <nav class="navbar navbar-projeto navbar-expand-lg">
            <div class="container-fluid d-flex justify-content-between align-items-center">
                <img class="animate__animated animate__fadeIn logo-delay img-fluid logo"
                    src="../assets/imgs/LOGO/inova-option-logo-branca.png" alt="Inova Option">
                <a href="https://inovaoption.com/auth/login"
                    class="animate__animated animate__fadeIn btn-delay btn btn-entrar" type="button">Entrar</a>
            </div>
        </nav>
    </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({})
export default class Navbar extends Vue { }
</script>

<style lang="scss">
@import '../scss/styles.scss';
</style>