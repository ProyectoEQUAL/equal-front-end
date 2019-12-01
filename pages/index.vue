<template>
    <div class="cd-section" id="headers" >
        <!--     *********     HEADER 1      *********      -->
        <div class="header-1">

            <div class="page-header header-filter">
                <div class="page-header-image" style="background-image: url('img/martin-balle-E2XN8sHBHSY-unsplash.jpg')"></div>
                <div class="content-center">
                    <div class="container">
                        <div class="row">
                            <div class="col-md-8 ml-auto text-right" style="background-color: rgba(93, 132, 166, 0.7); margin-top: 4.5em;">
                                <h1 class="title">Participa! Fem visible allò invisible</h1>
                                <h3 class="description">
                                    Sabíes que 1 de cada 10 dones majors de 15 anys ha patit algún tipus de violència masclista a Internet i a les Xarxes Socials?
                                </h3>
                                <br/>
                                <h3 class="description">
                                    Ajudan's a visibilitzar aquesta problemàtica social comentant a Instagram amb els hashtags <strong>#mesigualtat</strong> i <strong>#menysviolència</strong>, des del 5 fins al 19 de Desembre 
                                </h3>
                                <br/>
                                <div class="buttons">
                                    <a href="#pablo" class="btn btn-icon btn-link btn-neutral btn-lg">
                                        <i class="fab fa-instagram"></i>
                                    </a>
                                    <a href="#pablo">
                                         <n-button type="neutral"  size="lg" round simple><strong>Participa!</strong></n-button>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
  import { FormGroupInput, Button } from '@/components';
  import { Carousel, CarouselItem } from 'element-ui'
  export default {
    components:{
      [Button.name]: Button,
      [FormGroupInput.name]: FormGroupInput,
      [Carousel.name]: Carousel,
      [CarouselItem.name]: CarouselItem
    }
  }
</script>
<style>
</style>
