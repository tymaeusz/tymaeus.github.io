<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img style="height: 70px;" src="img/brand/void-light.png" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
               
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-ui-04 d-lg-none"></i>
                        <span class="nav-link-inner--text" style="font-size: large;">Void Works?</span>
                    </a>
                    <div class="dropdown-menu-inner">
                        <a href="https://github.com/void-works-br"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-indigo rounded-circle text-white">
                                <i class=" bi-github"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-indigo mb-md-1">Organização no Github</h6>
                            <p class="description d-none d-md-inline-block mb-0">Também é desenvolvedor freelancer? Venha fazer parte da iniciativa Void Works!</p>
                            </div>
                        </a>
                        <a href=""
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-purple rounded-circle text-white">
                                <i class="bi-discord"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-purple mb-md-1">Servidor no Discord</h5>
                                <p class="description d-none d-md-inline-block mb-0">Em breve teremos o servidor da Void Works, fique ligado!</p>
                            </div>
                        </a>
                    </div>
                </base-dropdown>
                <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-ui-04 d-lg-none"></i>
                        <span class="nav-link-inner--text" style="font-size: large;">Coming soon...</span>
                    </a>
                    <div class="dropdown-menu-inner">
                        <a href=""
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-light-purple rounded-circle text-white">
                                <i class="fa fa-clock-o"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-light-purple mb-md-1">Lorem...</h6>
                            <p class="description d-none d-md-inline-block mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. </p>
                            </div>
                        </a>
                        <a href=""
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-ultra-light rounded-circle text-white">
                                <i class="fa fa-clock-o"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-ultra-light mb-md-1">Ipsum...</h5>
                                <p class="description d-none d-md-inline-block mb-0">Nunc ante dui, facilisis sit amet luctus sit amet, gravida quis magna.  </p>
                            </div>
                        </a>
                    </div>
                </base-dropdown>
              
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://steamcommunity.com/id/tymaeus" target="_blank" rel="noopener"
                       title="Vamos jogar juntos na Steam!">
                        <i class="bi-steam"></i>
                        <span class="nav-link-inner--text d-lg-none">Steam</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.linkedin.com/in/janyel-lima/"
                       target="_blank" rel="noopener"  title="Siga-me ou conecte-se a mim no Linked In!">
                        <i class="bi-linkedin"></i>
                        <span class="nav-link-inner--text d-lg-none">Linked In</span>
                    </a>
                </li>
               
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://github.com/tymaeusz"
                       target="_blank" rel="noopener"  title="Confira meus repositórios públicos no Github!">
                        <i class="bi-github"></i>
                        <span class="nav-link-inner--text d-lg-none">Github</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://discordapp.com/users/222077757587324939"
                       target="_blank" rel="noopener"  title="Vem pro Discord ae!">
                        <i class="bi bi-discord"></i>
                        <span class="nav-link-inner--text d-lg-none">Discord</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
