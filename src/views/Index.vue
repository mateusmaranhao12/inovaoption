<template>
    <Navbar />
    <section class="secao-principal d-flex align-items-center">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-md-6 mt-5">
                    <h1>Negocie Ações, Forex e Criptomoedas</h1>
                    <p>Invista nos ativos mais populares e procurados do mundo com o jeito Inova de ser: sem delay,
                        somente no mercado real (sem OTC) de forma justa e transparente.
                        Registre-se grátis e receba R$30 reais de boas-vindas, 150% de bônus no seu primeiro depósito e
                        R$50.000 para sua conta de treinamento.
                    </p>
                    <div class="d-flex justify-content-md-start justify-content-center">
                        <button class="btn-negociar me-4">Negociar</button>
                        <button class="btn-conta-pratica">Conta Prática</button>
                    </div>
                </div>
                <div class="col-md-6 mt-5">
                    <img class="img-fluid" src="../assets/imgs/PLATAFORMA/MC/INOVA-OPTION-MOCKUP.png"
                        alt="Mockup Inova Option">
                </div>

                <div class="col-md-6 order-2 order-md-1 copy-inova">
                    <img class="img-fluid" src="../assets/imgs/PLATAFORMA/new-image-3.png"
                        alt="Mockup Inova Option">
                </div>
                <div class="col-md-6 order-1 order-md-2 copy-inova">
                    <h1>Copy Trade Inova</h1>
                    <p>Copie os melhores traders do mundo e lucre toda vez que eles lucrarem. Esta é a melhor ferramenta
                        para quem ainda não tem experiência e quer copiar um Trader lucrativo e experiente dentro da
                        Inova. Comece agora mesmo!
                    </p>
                    <div class="d-flex justify-content-md-start justify-content-center">
                        <button class="btn-copy-inova me-4">Quero o Copy Inova</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<script lang="ts">
import Navbar from '@/components/Navbar.vue'
import { Options, Vue } from 'vue-class-component'

@Options({

    components: {
        Navbar
    }

})
export default class Index extends Vue {
}
</script>

<style lang="scss">
@import '../scss/styles.scss';
</style>