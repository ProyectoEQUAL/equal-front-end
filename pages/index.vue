<template>
    <div class="cd-section" id="headers" >
        <!--     *********     HEADER 1      *********      -->
        <div class="header-1">

            <div class="page-header header-filter">
                <div class="page-header-image" style="background-image: url('img/rodion-kutsaev-IJ25m7fXqtk-unsplash.jpg')"></div>
                <div class="content-center">
                    <div class="container">
                        <div class="row" style=" margin-top: 4.5em;">
                            <div class="col-md-7 mr-auto text-left" style="">
                                <h1 class="title">Participa!</h1>
                                <h3 class="description">
                                    Ajudan's a visibilitzar la violència masclista a les Xarxes Socials comentant a Instagram amb els hashtags <strong>#mesigualtat</strong> i <strong>#menysviolencia</strong>, des del 5 fins al 19 de Desembre 
                                </h3>
                                <br/>
                                <div class="buttons text-right">
                                    <a href="#pablo" class="btn btn-icon btn-link btn-neutral btn-lg">
                                        <i class="fab fa-instagram"></i>
                                    </a>
                                    <a href="#pablo">
                                         <n-button type="neutral" size="lg" round simple><strong>Participa!</strong></n-button>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
            <!--     *********     END HEADER 1      *********      -->
            <!--     *********    PROJECTS 4     *********      -->
        <div class="projects-4">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-md-8 mr-auto ml-auto text-center">
                        <h6 class="category text-muted">Reflexionem sobre Igualtat de Gènere a Internet i a les Xarxes Socials</h6>
                        <h2 class="title">El Projecte EQUAL</h2>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 px-0">
                        <card class="card card-fashion" style="background: linear-gradient(45deg, rgba(131,58,180,1) 0%, rgba(253,29,29,1) 50%, rgba(252,176,69,1) 100%);;">
                            <div class="card-body">
                                <div class="card-footer text-left">
                                    <h2>
                                        Som iguals a Internet?
                                    </h2>
                                </div>
                            </div>
                        </card>
                    </div>
                    <div class="col-md-6 px-0">
                        <div class="card-container">
                            <div class="card card-fashion">
                                <div class="card-title">
                                    <a href="#pablo">
                                        <h4>
                                            Sabíes que 1 de cada 10 dones majors de 15 anys ha patit algún tipus de violència masclista a Internet i a les Xarxes Socials?
                                        </h4>
                                    </a>
                                </div>
                                <div class="card-body">
                                    <div class="card-footer">
                                        <div class="stats">
                                                <span>
                                                   #mesigualtat #menysviolencia
                                                </span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <card type="background" class="card-fashion"
                                  style="background-image: url('img/lalo-hernandez-r34cKhbEDCU-unsplash.jpg')">
                            </card>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 px-0">
                        <div class="card-container">
                            <card type="background" class="card-fashion"
                                  style="background-image: url('img/elena-koycheva-yJwbvWmJs5M-unsplash.jpg')">
                            </card>
                            <div class="card card-fashion arrow-left">
                                <div class="card-title">
                                    <h4>
                                        <a href="#pablo">
                                            Ajudan's a detectar imatges i textes que representin "Igualtat de Gènere" o "Violència masclista" des del teu feed d'Instagram.
                                        </a>
                                    </h4>
                                </div>
                                <div class="card-body">
                                    <div class="card-footer">
                                        <div class="stats">
                                               <span>
                                                   #mesigualtat #menysviolencia
                                                </span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 px-0">
                        <card class="card-fashion"
                              style="background-color: rgba(232, 193, 19) ">
                            <div class="card-body">
                                <div class="card-footer text-left">
                                    <h2>
                                        Del 5 al 19 de Desembre: <br>
                                        Fem visible allò invisible. Participa!
                                    </h2>
                                </div>
                            </div>
                            <div class="card-footer text-left">
                                <div class="stats">
                                    <span>
                                    </span>
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
            </div>
        </div>
        <!--     *********    END PROJECTS 4      *********      -->
    </div>

     
</template>
<script>
  import { FormGroupInput, Button, Card, InfoSection, Badge, Tabs, TabPane } from '@/components';
  import { Carousel, CarouselItem } from 'element-ui'
  export default {
    components:{
      Card,
      Tabs,
      TabPane,
      Badge,
      InfoSection,
      [Button.name]: Button,
      [FormGroupInput.name]: FormGroupInput,
      [Carousel.name]: Carousel,
      [CarouselItem.name]: CarouselItem
    }
  }
</script>
<style>
</style>
