<template>
    <Navbar />

    <!--Secao principal-->
    <section class="secao-principal d-flex align-items-center">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-md-6 mt-5">
                    <h1 class="animate__animated animate__fadeIn negocie-acoes-delay">Negocie Ações, <br> Forex e Criptomoedas</h1>
                    <p class="animate__animated animate__fadeIn p-delay">Invista nos ativos mais populares e procurados do mundo com o jeito Inova de ser: sem delay,
                        somente no mercado real (sem OTC) de forma justa e transparente.
                    </p>
                    <p class="animate__animated animate__fadeIn p-delay">Registre-se grátis e receba R$30 reais de boas-vindas, 150% de bônus no seu primeiro depósito e
                        R$50.000 para sua conta de treinamento.</p>
                    <div class="animate__animated animate__fadeIn btns-delay d-flex justify-content-md-start justify-content-center">
                        <a href="https://inovaoption.com/trade" class="btn-negociar me-3">Negociar</a>
                        <a href="https://inovaoption.com/auth/register" class="btn-conta-pratica">Conta de Prática</a>
                    </div>
                </div>
                <div class="animate__animated animate__fadeIn img-delay col-md-6 mt-5">
                    <img class="img-fluid" src="../assets/imgs/HOME NOVA/moackup-inova.png" alt="Mockup Inova Option">
                </div>
            </div>
        </div>
    </section>

    <!--Day Trade-->
    <section class="secao-copy-trade d-flex align-items-center" data-aos="fade-in">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-md-6 order-2 order-md-1 copy-inova">
                    <img class="animate__animated animate__fadeIn img-trade-delay img-fluid" src="../assets/imgs/PLATAFORMA/new-image-3.png" alt="Mockup Inova Option">
                </div>
                <div class="animate__animated animate__fadeIn trade-delay col-md-6 order-1 order-md-2 copy-inova">
                    <h1>Chegou! <br> Copy Trade Inova</h1>
                    <p>Copie os melhores traders do mundo e lucre toda vez que eles lucrarem. Esta é a melhor ferramenta
                        para quem ainda não tem experiência e quer copiar um Trader lucrativo e experiente enquanto
                        aprende. E também para você que tem experiência mas não tem tempo de negociar. <b>Comece agora
                            mesmo!</b>
                    </p>
                    <div class="d-flex justify-content-md-start justify-content-center">
                        <a href="https://inovaoption.com/auth/register" class="btn-copy-inova me-4">Abrir minha
                            conta</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!--Baixar App Inova-->
    <section class="secao-baixar-app" data-aos="fade-in">
        <div class="container animate__animated animate__fadeIn baixar-delay">
            <div class="row justify-content-center align-items-center">
                <div class="col-md-12 mt-5">
                    <h1 class="mb-4">Baixar App Inova</h1>
                    <p class="mb-4">Nossos aplicativos já estão disponíveis para Android e Desktop. Baixe agora e tenha
                        uma
                        experiência Inova. Clique para instalar</p>

                    <div class="d-flex justify-content-center flex-wrap mb-5 overflow-hidden">
                        <a href="https://api.inovaoption.com/assets/images/download/inova_option-ANDROID.apk">
                            <img style="height: 50px; cursor: pointer;" class="img-fluid me-3"
                                src="../assets/imgs/HOME NOVA/google-botao-inova.png" alt="Botão Google">
                        </a>
                        <a href="https://api.inovaoption.com/assets/images/download/InovaOption-WINDOWS.msi"><img
                                style="height: 50px; cursor: pointer;" class="img-fluid"
                                src="../assets/imgs/HOME NOVA/windows-botao-inova.png" alt="Botão Windows"></a>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!--Por que escolher-->
    <section class="por-que-escolher py-5" data-aos="fade-in">
        <div class="container">
            <div class="text-center mb-5">
                <h1>Por que escolher a InovaOption?</h1>
                <p>
                    A Inova Option se destaca por oferecer soluções flexíveis, suporte e acompanhamento especializado
                    e tecnologias avançadas para atender às suas necessidades no mercado. Além de presentes como
                    Bônus de entrada, Bônus de depósito e Cashback caso precise.
                </p>
            </div>
            <div class="row g-4 mb-5">
                <div class="col-md-4" v-for="(card, index) in cards" :key="index">
                    <div class="card h-100 shadow-sm">
                        <img :src="require(`../assets/imgs/${card.image}.jpg`)" class="card-img-top rounded-top"
                            :alt="card.title">
                        <div class="card-body">
                            <h5>{{ card.title }}</h5>
                            <p>{{ card.description }}</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="d-flex justify-content-center">
                <a href="https://inovaoption.com/auth/register" class="btn btn-receba mt-5 mb-5">Comece com R$30,00
                    grátis</a>
            </div>
        </div>
    </section>

    <!--Depositos e saques-->
    <section class="depositos-e-saques py-5" data-aos="fade-in">
        <div class="container text-center">
            <div class="mb-4">
                <p class="deposito-e-saque mb-1">DEPÓSITO E SAQUE</p>
                <h2>Depósitos e Retiradas Instantâneos</h2>
                <p>
                    Utilize seu pix ou escolha entre vários sistemas de pagamento para retirar e depositar seus fundos
                    de forma rápida e segura.<br>
                    Depósito Mínimo: R$60
                </p>
            </div>
            <div class="d-flex justify-content-center align-items-center gap-4 flex-wrap overflow-hidden">
                <img class="img-fluid" src="../assets/imgs/inova-pagamentos.png" style="cursor: pointer;">
            </div>
        </div>
    </section>

    <!--Etapas-->
    <section class="etapas py-5" data-aos="fade-in">
        <div class="container text-center">
            <p class="text-primary mb-1">Comece a Negociar em 3 Etapas</p>
            <h2 class="text-white mb-5">Simples, rápido e eficaz.</h2>
            <div class="row g-4">
                <div v-for="(etapa, index) in etapas" :key="index" class="col-md-4">
                    <div class="card etapa-card h-100">
                        <div class="card-body">
                            <div class="icon mb-3">
                                <i :class="etapa.icon" aria-hidden="true"></i>
                            </div>
                            <h5>{{ index + 1 }}. {{ etapa.title }}</h5>
                            <p>{{ etapa.description }}</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="d-flex justify-content-center">
                <a href="https://inovaoption.com/auth/register" class="btn btn-receba mb-3 mt-5">Comece com R$30,00
                    grátis</a>
            </div>
        </div>
    </section>

    <!--Footer-->
    <Footer data-aos="fade-in" />

</template>

<script lang="ts">
import Footer from '@/components/Footer.vue'
import Navbar from '@/components/Navbar.vue'
import { Options, Vue } from 'vue-class-component'
import AOS from 'aos'
import 'aos/dist/aos.css'

@Options({

    components: {
        Navbar,
        Footer
    }

})
export default class Index extends Vue {

    mounted() {
        AOS.init({
            duration: 1000, // Duração da animação (1 segundo)
            once: true, // Anima apenas na primeira rolagem (evita repetição)
        })
    }

    cards = [
        {
            image: 'meta__img',
            title: 'Plataforma de fácil utilização',
            description: 'Desenvolvida para atender desde os leigos até investidores experientes, a Inova Option oferece uma plataforma intuitiva e funcional.'
        },

        {
            image: 'inova-option2',
            title: 'Payout fixo mais alto do mercado',
            description: 'Oferecemos um dos maiores payouts disponíveis, proporcionando controle total das suas decisões e máximo desempenho.'
        },

        {
            image: 'inova-suporte',
            title: 'Suporte humano e disponível 24h',
            description: 'Nossa equipe de suporte está sempre pronta para ajudar, oferecendo atendimento humanizado 24 horas por dia.'
        }
    ]

    etapas = [
        {
            icon: 'fas fa-user-plus',
            title: 'Inscreva-se',
            description: 'Abra sua conta gratuitamente em instantes.'
        },

        {
            icon: 'fas fa-chalkboard-teacher',
            title: 'Pratique',
            description: 'Desenvolva e domine suas habilidades com uma conta de prática e conteúdo educacional.'
        },

        {
            icon: 'fas fa-money-bill-wave',
            title: 'Deposite e Negocie',
            description: 'Mais de 250 instrumentos com depósito mínimo de 60 reais para uma negociação definitiva.'
        }
    ]

}
</script>

<style lang="scss">
@import '../scss/styles.scss';
</style>