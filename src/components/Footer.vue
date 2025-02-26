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
                        <li><a href="#">Questões gerais</a></li>
                        <li><a href="#">Questões financeiras</a></li>
                        <li><a href="#">Verificação</a></li>
                    </ul>
                </div>

                <!-- Sobre Nós -->
                <div class="col-md-2">
                    <h5>Sobre nós <span class="arrow">&gt;</span></h5>
                    <ul class="list-unstyled">
                        <li><a href="#">Contatos</a></li>
                    </ul>
                </div>

                <!-- Mais e Aplicativo -->
                <div class="col-md-2">
                    <h5>Mais</h5>
                    <ul class="list-unstyled">
                        <li><a href="#">Conta demo</a></li>
                        <li><a href="#">Programa de afiliados <i class="fas fa-external-link-alt"></i></a></li>
                    </ul>
                </div>

                <div class="col-md-4">
                    <h6 >Descarregar a aplicação</h6>
                    <a href="#" class="d-flex justify-content-md-start justify-content-center mt-2 mb-4">
                        <img src="../assets/imgs/HOME NOVA/google-botao-inova.png" style="height: 50px;"
                            class="img-fluid">
                    </a>
                    <h6>Siga-nos nas redes sociais</h6>
                    <div class="social-icons d-flex flex-column gap-2 mt-2">
                        <a href="#" class="btn-social"> <i class="fab fa-facebook"></i> 10K+</a>
                        <a href="#" class="btn-social"> <i class="fab fa-instagram"></i> 76K+</a>
                        <a href="#" class="btn-social"> <i class="fab fa-telegram"></i> 90K+</a>
                    </div>
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