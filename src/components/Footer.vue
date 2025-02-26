<template>
    <footer class="rodape py-5">
        <div class="container bg-footer">
            <div class="row">
                <!-- Seção da Logo -->
                <div class="col-md-2">
                    <img src="../assets/imgs/LOGO/inova-option-logo-branca.png" style="height: 25px;"
                        class="img-fluid mb-4">
                </div>

                <!-- Perguntas Frequentes -->
                <div class="col-md-2">
                    <h5>Perguntas frequentes <span class="arrow">&gt;</span></h5>
                    <ul class="list-unstyled">
                        <li><a href="https://pt.inovaoption.com/faq" target="_blank">Questões gerais</a></li>
                        <li><a href="https://pt.inovaoption.com/faq/#financial" target="_blank">Questões financeiras</a>
                        </li>
                        <li><a href="https://pt.inovaoption.com/faq/#verification" target="_blank">Verificação</a></li>
                    </ul>
                </div>

                <!-- Ajuda -->
                <div class="col-md-2">
                    <h5>Ajuda <span class="arrow">&gt;</span></h5>
                    <ul class="list-unstyled">
                        <li><a href="#">E-mail</a></li>
                        <li><a href="mailto:support@inovaoption.com" target="_blank">support@inovaoption.com</a></li>
                    </ul>
                </div>

                <!-- Mais e Aplicativo -->
                <div class="col-md-2">
                    <h5>Mais</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://inovaoption.com/auth/register" target="_blank">Conta demo</a></li>
                        <li><a href="https://inovaoption.com/affiliate" target="_blank">Programa de afiliados <i
                                    class="fas fa-external-link-alt"></i></a></li>
                    </ul>
                </div>

                <div class="col-md-4">
                    <h6>Descarregar a aplicação</h6>
                    <div class="download-buttons mt-2 mb-4">
                        <a href="https://api.inovaoption.com/assets/images/download/inova_option-ANDROID.apk"
                            target="_blank">
                            <img src="../assets/imgs/HOME NOVA/google-botao-inova.png" class="img-fluid"
                                alt="Google Play">
                        </a>
                        <a href="https://api.inovaoption.com/assets/images/download/InovaOption-WINDOWS.msi"
                            target="_blank">
                            <img src="../assets/imgs/HOME NOVA/windows-botao-inova.png" class="img-fluid" alt="Windows">
                        </a>
                    </div>

                    <h6>Siga-nos nas redes sociais</h6>
                    <div class="social-icons d-flex flex-column mt-2">
                        <a href="https://www.facebook.com/inovaoption" target="_blank"
                            class="btn-social text-md-start text-center"> <i class="fab fa-facebook"></i>
                            Facebook</a>
                        <a href="https://www.instagram.com/inovaoption" target="_blank"
                            class="btn-social text-md-start text-center"> <i class="fab fa-instagram"></i>
                            Instagram</a>
                        <a href="https://t.me/inovaoption" target="_blank" class="btn-social text-md-start text-center">
                            <i class="fab fa-telegram"></i>
                            Telegram</a>
                        <a href="https://www.youtube.com/@inovaoption" target="_blank"
                            class="btn-social text-md-start text-center">
                            <i class="fab fa-youtube"></i>
                            YouTube</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-md-4 mt-5">
                    <h5 class="mb-4">Regulamentos</h5>
                    <ul class="list-unstyled">
                        <li><a class="regulamentos" href="https://pt.inovaoption.com/politica-de-privacidade"
                                target="_blank">Política de privacidade</a></li>
                        <li><a class="regulamentos" href="https://pt.inovaoption.com/termos-de-uso"
                                target="_blank">Acordo de serviço</a></li>
                        <li><a class="regulamentos" href="https://pt.inovaoption.com/advertencia-de-risco"
                                target="_blank">Advertência de risco</a></li>
                        <li><a class="regulamentos" href="https://pt.inovaoption.com/riscos" target="_blank">Regras de
                                operacões comerciais</a></li>
                        <li><a class="regulamentos" href="https://pt.inovaoption.com/politica-de-pagamento"
                                target="_blank">Política de pagamento</a></li>
                    </ul>
                </div>

                <div class="col-md-8 mt-5">
                    <p>Os serviços do site não estão disponíveis em vários países, incluindo EUA, Canadá, Hong Kong,
                        países do EEE, Israel e Rússia, bem como para pessoas com menos de 18 anos de idade.</p>

                    <p>Aviso de risco: a negociação de Forex e instrumentos financeiros alavancados envolve risco
                        significativo e pode resultar na perda de seu capital investido. Você não deve investir mais do
                        que pode perder, e deve certificar-se de que compreende totalmente os riscos envolvidos. A
                        negociação de produtos alavancados pode não ser adequada para todos os investidores. A
                        negociação de produtos não alavancados, como ações, também envolve risco, pois o valor de uma
                        ação pode tanto cair quanto subir, o que pode resultar em um rendimento menor do que o investido
                        originalmente. O desempenho passado não é garantia de resultados futuros. Antes de negociar,
                        leve em consideração seu nível de experiência e objetivos de investimento e procure
                        aconselhamento financeiro independente, se necessário. É responsabilidade do cliente verificar
                        se tem permissão para utilizar os serviços da marca Quotex de acordo com os requisitos legais de
                        seu país de residência.</p>

                    <p>Copyright ©️ 2025 InovaOption. Todos os direitos reservados</p>
                </div>
            </div>
        </div>
    </footer>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({})
export default class Footer extends Vue {

}
</script>

<style lang="scss">
@import '../scss/styles.scss';
</style>