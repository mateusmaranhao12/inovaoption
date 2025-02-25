<template>
    <footer class="rodape py-5">
        <div class="container">
            <div class="row">
                <!-- Seção da Logo e Descrição -->
                <div class="col-md-4">
                   <img src="../assets/imgs/LOGO/inova-option-logo-branca.png" style="height: 30px;" class="img-fluid">
                    <p class="mt-3">
                        Inova Option fornece seus serviços exclusivamente nos territórios em que é licenciada. Inova
                        Option não está
                        autorizada pela Comissão de Valores Mobiliários (CVM) a oferecer diretamente serviços de
                        distribuição de valores
                        mobiliários a investidores residentes, domiciliados ou incorporados na República Federativa do
                        Brasil. Nada
                        neste site deve ser entendido como uma oferta direta de serviços endereçados a esses
                        investidores.
                    </p>
                </div>

                <!-- Seção de Política e Termos -->
                <div class="col-md-4 text-center">
                    <h5 class="text-white mb-3">Política e Termos</h5>
                    <ul class="list-unstyled">
                        <li><a href="#">Programa de Afiliados</a></li>
                        <li><a href="#">Política de Privacidade</a></li>
                        <li><a href="#">Termos & Condições</a></li>
                    </ul>
                </div>

                <!-- Seção de Ajuda -->
                <div class="col-md-4">
                    <h5 class="text-white mb-3">Ajuda</h5>
                    <ul class="list-unstyled">
                        <li><a href="#">Central de Ajuda</a></li>
                        <li><a href="mailto:support@inovaoption.com">support@inovaoption.com</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({})
export default class Footer extends Vue { }
</script>

<style lang="scss">
@import '../scss/styles.scss';
</style>
