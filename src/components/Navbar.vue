<template>
    <div class="container-menor mt-3">
        <nav class="navbar navbar-projeto navbar-expand-lg">
            <div class="container-fluid">
                <img class="img-fluid" src="../assets/imgs/LOGO/inova-option-logo-branca.png">
                <button class="btn btn-entrar" type="button">Entrar</button>
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