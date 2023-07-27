<template>
    <footer class="footer has-cards">

      

        <div class="container container-lg">
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <a title="Sistemas full code!">
                            <img v-lazy="'img/theme/void-code.png'" class="card-img">
                        </a>
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <a title="Sistemas totalmente coustomizáveis!">
                            <img v-lazy="'img/theme/void-spring.png'" class="card-img">
                        </a>
                    </div>
                </div>
            </div>
        </div>

        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h3 style="color: #e0aaff;" class="font-weight-bold mb-2">Obrigado pela visita!</h3>
                    <h4 style="color: white;" class="mb-0 font-weight-bold">Entre em contato via plataformas.</h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper">

                    <a target="_blank" rel="noopener" href="https://steamcommunity.com/id/tymaeus"
                        class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg"
                        title="Vamos jogar juntos na Steam!">
                        <i class="bi-steam"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://www.linkedin.com/in/janyel-lima/"
                        class="btn btn-facebook btn-icon-only btn-linkedin btn-round btn-lg"
                        title="Siga-me ou conecte-se a mim no Linked In!">
                        <i class="bi-linkedin"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://github.com/tymaeusz"
                        class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg"
                        title="Confira meus repositórios públicos no Github! ">
                        <i class=" bi-github"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://discordapp.com/users/222077757587324939"
                        class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" title="Vem pro Discord ae!">
                        <i class="bi-discord"></i>
                    </a>
                </div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div style="color: white;" class="copyright font-weight-bold">
                        &copy; {{ year }}
                        <a class="font-weight-bold" style="color: white;" href="https://tymaeus.dev" target="_blank"
                            rel="noopener">Janyel B. Lima (Tymaeus) </a>
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a style="color: white!important;" href="https://pages.github.com/"
                                class="nav-link font-weight-bold" target="_blank" rel="noopener">GitHub Pages</a>
                        </li>


                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
    name: 'app-footer',
    data() {
        return {
            year: new Date().getFullYear()
        }
    }
};

</script>
<style>
.footer.has-cards:before {

    background: linear-gradient(150deg, #3c096c 15%, #5a189a 70%, #7b2cbf 94%) !important;

}</style>