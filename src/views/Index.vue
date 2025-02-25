<template>
    <Navbar />

    <!--Secao principal-->
    <section class="secao-principal d-flex align-items-center">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-md-6 mt-5">
                    <h1>Negocie Ações, <br> Forex e Criptomoedas</h1>
                    <p>Invista nos ativos mais populares e procurados do mundo com o jeito Inova de ser: sem delay,
                        somente no mercado real (sem OTC) de forma justa e transparente.
                    </p>
                    <p>Registre-se grátis e receba R$30 reais de boas-vindas, 150% de bônus no seu primeiro depósito e
                        R$50.000 para sua conta de treinamento.</p>
                    <div class="d-flex justify-content-md-start justify-content-center">
                        <button class="btn-negociar me-3">Negociar</button>
                        <button class="btn-conta-pratica">Conta Prática</button>
                    </div>
                </div>
                <div class="col-md-6 mt-5">
                    <img class="img-fluid" src="../assets/imgs/HOME NOVA/moackup-inova.png" alt="Mockup Inova Option">
                </div>
            </div>
        </div>
    </section>

    <!--Day Trade-->
    <section class="secao-copy-trade d-flex align-items-center">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-md-6 order-2 order-md-1 copy-inova">
                    <img class="img-fluid" src="../assets/imgs/PLATAFORMA/new-image-3.png" alt="Mockup Inova Option">
                </div>
                <div class="col-md-6 order-1 order-md-2 copy-inova">
                    <h1>Chegou! <br> Copy Trade Inova</h1>
                    <p>Copie os melhores traders do mundo e lucre toda vez que eles lucrarem. Esta é a melhor ferramenta
                        para quem ainda não tem experiência e quer copiar um Trader lucrativo e experiente dentro da
                        Inova. <b>Comece agora mesmo!</b>
                    </p>
                    <div class="d-flex justify-content-md-start justify-content-center">
                        <button class="btn-copy-inova me-4">Abrir minha conta</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!--Baixar App Inova-->
    <section class="secao-baixar-app">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-md-12 mt-5">
                    <h1 class="mb-4">Baixar App Inova</h1>
                    <p class="mb-4">Nossos aplicativos já estão disponíveis para Android e Desktop. Baixe agora e tenha
                        uma
                        experiência Inova. Clique para instalar</p>
                        
                    <div class="d-flex justify-content-center flex-wrap mb-5 overflow-hidden">
                        <img style="height: 50px; cursor: pointer;" class="img-fluid me-3"
                            src="../assets/imgs/HOME NOVA/google-botao-inova.png" alt="Botão Google">
                        <img style="height: 50px; cursor: pointer;" class="img-fluid"
                            src="../assets/imgs/HOME NOVA/windows-botao-inova.png" alt="Botão Windows">
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!--Por que escolher-->
    <section class="por-que-escolher">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <h1>Por que escolher a InovaOption?</h1>
                    <p>A Inova Option se destaca por oferecer soluções flexíveis, suporte e acompanhamento especializado
                        e tecnologias avançadas para atender às suas necessidades no mercado. Além de presentes como
                        Bônus de entrada, Bônus de depósito e Cashback caso precise.</p>
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