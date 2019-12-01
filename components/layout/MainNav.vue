<template>
    <navbar position="fixed"
            :transparent="transparent"
            :color-on-scroll="colorOnScroll"
            menu-classes="ml-auto">
        <template slot-scope="{toggle, isToggled}">
                <nuxt-link v-popover:popover1 class="navbar-brand" to="/">
                    EQUAL
                </nuxt-link>
                <el-popover
                        ref="popover1"
                        popper-class="popover"
                        placement="bottom"
                        width="300"
                        trigger="hover">
                    <div class="popover-body">Created with love by EQUAL</div>
                </el-popover>
        </template>
        <template slot="navbar-menu">
            <drop-down tag="li" title="Menu" icon="now-ui-icons design_app" class="nav-item">
                <nav-link to="/about">
                    <i class="now-ui-icons design_image"></i> About Equal
                </nav-link>
                <nav-link to="/contact">
                    <i class="now-ui-icons business_chart-pie-36"></i> Contact us
                </nav-link>
                <a href="https://demos.creative-tim.com/nuxt-now-ui-kit-pro/documentation" target="_blank" class="dropdown-item">
                    <i class="now-ui-icons design_bullet-list-67"></i> Documentation
                </a>
            </drop-down>
        </template>
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
