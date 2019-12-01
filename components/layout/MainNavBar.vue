<template>
    <navbar position="fixed"
            :transparent="transparent"
            :color-on-scroll="colorOnScroll"
            menu-classes="ml-auto">
                    <nav class="navbar navbar-expand-lg navbar-transparent bg-success navbar-absolute">
                <div class="container">
                    <div class="navbar-translate">
                        <button class="navbar-toggler" type="button" data-toggle="collapse"
                                data-target="#example-navbar-success" aria-controls="navbarSupportedContent"
                                aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-bar bar1"></span>
                            <span class="navbar-toggler-bar bar2"></span>
                            <span class="navbar-toggler-bar bar3"></span>
                        </button>
                        <a class="navbar-brand" href="#">Equal</a>
                    </div>
                    <div class="collapse navbar-collapse" id="example-navbar-success2">
                        <ul class="navbar-nav mx-auto">
                            <li class="nav-item active">
                                <a class="nav-link" href="#">
                                    Home
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">
                                    About Us
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">
                                    Contact Us
                                </a>
                            </li>
                        </ul>
                        <ul class="nav navbar-nav">
                            <li class="nav-item">
                                <a class="nav-link" href="">
                                    <i class="fab fa-twitter"></i>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="">
                                    <i class="fab fa-facebook-square"></i>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="">
                                    <i class="fab fa-instagram"></i>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
    </navbar>
</template>

<script>
  import { DropDown, NavbarToggleButton, Navbar, NavLink } from '@/components';
  import { Popover } from 'element-ui'
  export default {
    name: 'main-navbar',
    props: {
      transparent: Boolean,
      colorOnScroll: Number,
    },
    components: {
      DropDown,
      Navbar,
      NavbarToggleButton,
      NavLink,
      [Popover.name]: Popover
    }
  }
</script>

<style scoped>

</style>
