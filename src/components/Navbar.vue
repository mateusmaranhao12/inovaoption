<template>
        <nav class="navbar navbar-projeto navbar-expand-lg">
            <div class="container-fluid">
                <img class="img-fluid" src="../assets/imgs/LOGO/INOVA-OPTION-BRANCO-2.png">
                <button class="btn btn-entrar" type="button">Entrar</button>
            </div>
        </nav>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({})
export default class Navbar extends Vue { }
</script>

<style lang="scss">
@import '../scss/styles.scss';
</style>