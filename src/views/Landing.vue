<template>
    <div>

        <div class="position-relative ">
            <!-- shape Hero -->
            <section class="section-shaped my-0 " style="">
                <div class="shape shape-style-1 shape-default shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>

                <div class="container shape-container d-flex">
                </div>


            </section>

        </div>


        <section class="section section-lg pt-lg-0 mt--200">
            <div class="profile-page">
                <section class="section section-skew">
                    <div class="container">
                        <card shadow body-classes="py-10" style="background: linear-gradient(150deg, #3c096c 15%, #5a189a 70%, #7b2cbf 94%);border-radius: 10px;"
                            class="card-profile mt--300" no-body>
                            <div class="px-4">
                                <div class="row justify-content-center">
                                    <div class="col-lg-3 order-lg-2">
                                        <div class="card-profile-image">
                                            <a href="#">
                                                <img v-lazy="'img/theme/janyel-lima.jpg'" class="rounded-circle">
                                            </a>
                                        </div>
                                    </div>
                                    <div class="col-lg-4 order-lg-3 text-lg-right align-self-lg-center">
                                        <div class="card-profile-actions py-4 mt-lg-0">
                                            <base-button role="button" tag="a" target="_blank"
                                                href="mailto:janyel.lima2809@outlook.com" type="light-purple"
                                                icon="fa fa-envelope" size="sm" class="mr-4">Enviar
                                                e-mail</base-button>
                                            <base-button role="button" tag="a" target="_blank"
                                                href="https://wa.me//5582999712833?text=Ol%C3%A1%20Janyel%21%20Eu%20vim%20at%C3%A9%20seu%20contato%20atrav%C3%A9s%20do%20site."
                                                type="ultra-light" icon="fa fa-whatsapp" size="sm"
                                                class="float-right">Whatsapp</base-button>
                                        </div>
                                        
                                    </div>
                                    <div class="col-lg-4 order-lg-1">
                                        <div class="card-profile-stats d-flex justify-content-center">
                                            <div>
                                                <span style="color: #e0aaff;" class="heading">{{ dolar }}</span>
                                                <span style="color: white;"
                                                    class="description font-weight-bold">Dólar (diário)</span>
                                            </div>
                                            <div>
                                                <span style="color: #e0aaff;" class="heading">{{ inflacao }}%</span>
                                                <span style="color: white;"
                                                    class="description font-weight-bold">IPCA (mensal)</span>
                                            </div>
                                            <div>
                                                <span style="color: #e0aaff;" class="heading">{{ repos }}</span>
                                                <span style="color: white;"
                                                    class="description font-weight-bold">Repositórios públicos</span>
                                            </div>
                                          
                                        </div>
                                    </div>
                                </div>
                                <div class="text-center mt-5">
                                    <h3 style="color: white;">Janyel B. Lima<span style="color: white;"
                                            class="font-weight-bold">, {{ age }}</span>
                                    </h3>
                                    <div style="color: white;" class="h6 font-weight-400"><i
                                            class="ni location_pin mr-2"></i>Arapiraca, Alagoas -
                                        Brazil
                                    </div>
                                    <div style="color: white;" class="h6 mt-4 font-weight-400"><i
                                            class="ni business_briefcase-24 mr-2"></i>Desenvolvedor Java
                                        Fullstack -
                                        Freelancer/Void Works</div>
                                    <div style="color: white;"><i
                                            class="ni education_hat mr-2 font-weight-400"></i>Universidade Estadual de
                                        Alagoas</div>
                                </div>
                                <div class="mt-5 py-5 border-top text-center">
                                    <div class="row justify-content-center">
                                        <div class="col-lg-9">
                                            <p style="text-align: justify;line-height: 1.6;  margin: 0 0 16px;color: white;"
                                                class="font-weight-bold">
                                                Olá! Sou Janyel Barbosa Lima, um Desenvolvedor de Software com habilidades
                                                em Business Intelligence (MS Power BI) e consultoria de processos (BPMN).
                                                Tenho dedicado 4 anos ao aprimoramento nesse segmento, com experiência desde
                                                minha trajetória na <a style="color: #e0aaff;" class="font-weight-bold"
                                                    href="https://vale-verde.com/">Mineração Vale
                                                    Verde</a> até trabalhos como desenvolvedor freelancer em parceria com a
                                                <a style="color: #e0aaff;" class="font-weight-bold"
                                                    href="https://automining.com.br/">Automining</a>.
                                            </p>
                                            <p style="text-align: justify;line-height: 1.6;  margin: 0 0 16px;color: white;"
                                                class="font-weight-bold">
                                                Estou animado em buscar novas parcerias e possíveis contratos. Se você
                                                deseja otimizar seus processos de negócio e ter acesso a soluções poderosas,
                                                entre em contato comigo para agendarmos uma reunião. Vamos juntos construir
                                                soluções que impulsionarão seu negócio para o sucesso!

                                            </p>
                                           
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </card>
                    </div>
                </section>
            </div>


            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div  class="col-lg-4">
                                <card style="border-radius: 10px;" class="border-0" hover shadow body-classes="py-10">
                                    <icon name="fa fa-code" type="light-purple" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-light-purple text-uppercase display-5 font-weight-bold">Software
                                        Development</h6>
                                    <p style="text-align: justify;"  class="description mt-3 font-weight-bold">Automatize seus processos com meus serviços
                                        de
                                        desenvolvimento de software. Cristalize suas ideias em soluções de software
                                        personalizadas, juntos criaremos sistemas elegantes que transformam seus desafios em
                                        oportunidades!</p>
                                    <div>
                                        <badge type="light-purple" rounded>desenvolvimento</badge>
                                        <badge type="light-purple" rounded>software</badge>
                                        <badge type="light-purple" rounded>tecnologia</badge>
                                    </div>
                                    <base-button target="_blank" tag="a" href="https://fia.com.br/blog/desenvolvimento-de-softwares/" type="light-purple" class="mt-4">
                                        Saber mais
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" style="border-radius: 10px;" hover shadow body-classes="py-10">
                                    <icon name="fa fa-bar-chart" type="indigo" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-indigo text-uppercase display-5 font-weight-bold">Business Intelligence
                                    </h6>
                                    <p style="text-align: justify;"  class="description mt-3 font-weight-bold">No mundo acelerado de hoje, ter insights em
                                        tempo real ao
                                        seu alcance é a chave para tomar decisões informadas. Com o Power B.I., você pode
                                        liberar o verdadeiro potencial de seus dados, transformando números brutos em
                                        inteligência acionável. </p>
                                    <div>
                                        <badge type="indigo" rounded>Intenligência de Negócios</badge>
                                        <badge type="indigo" rounded>Dados</badge>
                                        <badge type="indigo" rounded>Power BI</badge>
                                    </div>
                                    <base-button target="_blank" tag="a" href="https://powerbi.microsoft.com/pt-br/"
                                        type="indigo" class="mt-4">
                                        Saber mais
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-1" style="border-radius: 10px;" hover shadow body-classes="py-10">
                                    <icon name="fa fa-line-chart" type="purple" rounded class="mb-4">

                                    </icon>

                                    <h6  class="text-purple text-uppercase display-5 font-weight-bold">Business Process</h6>
                                    <p style="text-align: justify;"  class="description mt-3 font-weight-bold">Explore futuro da otimização de negócios
                                        com BPMN (Business Process Model and Notation). Eleve o desempenho de sua empresa',
                                        pois o BPMN permite que você orquestre fluxos de trabalho complexos com precisão
                                        cirúrgica.</p>
                                    <div>
                                        <badge type="purple" rounded>processo de negócio</badge>
                                        <badge type="purple" rounded>bpmn</badge>
                                        <badge type="purple" rounded>otimização</badge>
                                    </div>
                                    <base-button target="_blank" tag="a" href="https://camunda.com/bpmn/" type="purple"
                                        class="mt-4">
                                        Saber mais
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg"
            style="background: linear-gradient(150deg, #be92ff 30%, #3c096c 80%, #240046 94%)!important;">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <img src="img/theme/promo-1.png" class="img-fluid floating">
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <icon name="ni ni-settings" class="mb-5 text-white" size="lg" type="indigo" shadow rounded></icon>
                            <h3 style="color: #3C096C;font-weight: bold;">Soluções customizáveis</h3>
                            <p style="color: white;text-align: justify;" class="font-weight-bold">Reconhecendo que cada cliente é único, procuro
                                focar minha abordagem em criar soluções sob medida, adaptadas às suas necessidades
                                específicas. Almejando a transparência no desenvolvimento e entrega da solução, assim como
                                na negociação. </p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="indigo" circle class="mr-3 text-white" icon="fa fa-code"></badge>
                                        <h6 style="color: white;" class="mb-0 font-weight-bold">Sistemas desenvolvidos
                                            cuidadosamente</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="indigo" circle class="mr-3 text-white" icon="fa fa-line-chart"></badge>
                                        <h6 style="color: white;" class="mb-0 font-weight-bold">Otimização dos processos da
                                            organização</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="indigo" circle class="mr-3 text-white" icon="ni ni-satisfied"></badge>
                                        <h6 style="color: white;" class="mb-0 font-weight-bold">Suporte e compromisso com o
                                            cliente</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section bg-white">

            <div  class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div style="border-radius: 10px;" class="card bg-indigo shadow border-0">
                            <img style="border-radius: 10px;" v-lazy="'img/theme/meet.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                    class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" fill="#5603ad"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" fill="#5603ad"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">Transparência</h4>
                                <p style="text-align: justify;" class="lead text-italic text-white font-weight-bold">No âmbito das negociações, a adoção de uma abordagem
                                    transparente traz inúmeras vantagens técnicas. Negociações transparentes promovem uma
                                    cultura de comunicação aberta, permitindo que todas as partes compartilhem livremente
                                    informações, dados e insights vitais.</p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <icon name="fa fa-user" class="mb-5" size="lg" type="indigo" shadow rounded></icon>

                            <h3 class="font-weight-bold">Ênfase no cliente</h3>
                            <p style="text-align: justify;"  class="lead font-weight-bold">Com o cenário de negócios em constante evolução, a chave estratégica para obter
                                resultados triunfantes reside no alinhamento da execução dos projetos com a bússola das
                                expectativas dos meus clientes.</p>
                            <p style="text-align: justify;" class="font-weight-bold">Contar com a expertise do próprio cliente para garantir uma solução única e com a cara dele é
                                um dos muitos caminhos para desenvolver um bom relacionamento.</p>


                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid justify-content-center">
                    <div class="col-lg-8 text-center">
                        <h2 class="display-3 text-purple font-weight-bold">Não apenas clientes, parceiros também!
                        
                        </h2>
                        <p style="text-align: justify;" class="lead font-weight-bold">Cada solução criada é o resultado de um esforço em colaboração memorável entre o desenvolvedor e o cliente, uma sinergia que garante o sucesso de ambos e forja uma relação de confiança sólida. Evidenciar esse relacionamento é sinônimo de compartilhar o sucesso conquistado junto aos nossos valiosos clientes!</p>
                        <div class="btn-wrapper">
                            <a target="_blank" href="mailto:janyel.lima2809@outlook.com"
                                class="btn btn-indigo mb-3 mb-sm-0">Quero fazer parte!</a>
                        </div>
                        <div class="text-center">
                            <h4 class="display-4 mb-5 mt-5">Clientes e parceiros</h4>
                            <div class="row justify-content-center">
                                <div class="col-lg-2 col-4">
                                    <a href="https://automining.com.br/" target="_blank" title="Automining - Business Process Intelligence">
                                        <img style="border-radius: 10px;"
                                            v-lazy="'https://media.licdn.com/dms/image/D4D0BAQGMRS0UgC3KnA/company-logo_200_200/0/1684761255518?e=1698278400&v=beta&t=PCpO1Oj3AMbrYSidr9dmhc1_tOZTnhZQlO2Pv3eWD08'"
                                            class="img-fluid">
                                    </a>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>


    </div>
</template>

<script>
import axios from 'axios';
export default {
    name: "home",
    data() {
        return {
            birthDate: '2000-09-28',
            age: null,
            dolar: null,
            inflacao: null,
            githubuser: [],
            repos: null
        };
    },
    methods: {

        calculateAge(birthDate) {
            const birthDateObj = new Date(birthDate);
            const today = new Date();

            let age = today.getFullYear() - birthDateObj.getFullYear();
            const monthDiff = today.getMonth() - birthDateObj.getMonth();

            if (monthDiff < 0 || (monthDiff === 0 && today.getDate() < birthDateObj.getDate())) {
                age--;
            }

            return age;
        },

        updateAgePeriodically() {
            this.age = this.calculateAge(this.birthDate);

            // Update the age every 1 second (adjust this interval as desired)
            setInterval(() => {
                this.age = this.calculateAge(this.birthDate);
            }, 1000);
        },

        formatCurrency(value) {
            return new Intl.NumberFormat('pt-BR', { style: 'currency', currency: 'BRL' }).format(value);
        },

        async fetchData() {
            try {
                const response = await axios.get('https://economia.awesomeapi.com.br/last/USD-BRL');
                const high = response.data.USDBRL.high;
                this.dolar = this.formatCurrency(high);
            } catch (error) {
                console.error('Erro ao buscar dados da API :', error);
            }
        },

        async fetchBacenData() {
            try {
                const response = await axios.get('https://api.bcb.gov.br/dados/serie/bcdata.sgs.433/dados');
                const currentDate = new Date();
                const currentYear = currentDate.getFullYear();
                const currentMonth = currentDate.getMonth();
                const dataMatchingCurrentMonth = response.data.find(item => {

                    const [day, month, year] = item.data.split('/').map(Number);

                    const itemDate = new Date(year, month, day);
  
                    return itemDate.getFullYear() === currentYear && itemDate.getMonth() === currentMonth;
                    });

                   

                if (dataMatchingCurrentMonth) {
                    this.inflacao = dataMatchingCurrentMonth.valor;
                } else {
                    this.inflacao = null;
                }



            } catch (error) {
                console.error('Error fetching API data:', error);
            }
        },

        async fetchGitHubData() {
            try {
                const response = await axios.get('https://api.github.com/users/tymaeusz');
                const githubUser = response.data;
                this.githubuser = githubUser;
                this.repos = githubUser.public_repos;

            } catch (error) {
                console.error('Error fetching API data:', error);
                this.loading = false;
            }
        }

    },
    computed: {
        formattedValorDolar() {
            return this.dolar;
        },
        fetchedInflacaoMensal() {
            return this.in,flacao;
        },
        fetchedGithubUser(){
            return this.githubuser;
        }
    },


    created() {
        this.updateAgePeriodically();

        // Fetch the API data immediately when the component is created
        this.fetchData();
        this.fetchBacenData();
        this.fetchGitHubData();

        // Fetch the API data every 5 seconds (adjust the interval as needed)
        this.fetchInterval = setInterval(this.fetchData, 5000),setInterval(this.fetchBacenData,60000);setInterval(this.fetchGitHubData,60000);
    },
    beforeDestroy() {

        // Clear the interval when the component is destroyed to prevent memory leaks
        clearInterval(this.fetchInterval);
    }

};

</script>
  
