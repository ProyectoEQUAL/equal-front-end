<template>
    <footer class="footer"
            :class="{[`footer-${type}`]: type}"
            :data-background-color="backgroundColor">
        <div class="container">
            <nav>
                <ul>
                    <li>
                        <a href="">
                            Lorem Ipsum
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Lorem Ipsum
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Lorem Ipsum
                        </a>
                    </li>
                    <li>
                        <a href="">
                           Lorem Ipsum
                        </a>
                    </li>
                </ul>
            </nav>
            <div class="copyright">
                &copy; {{year}}, Created by
                <a href="" target="_blank" rel="noopener" class="text-success">Equal</a>.
            </div>
        </div>
    </footer>
</template>
<script>
  export default {
    props: {
      backgroundColor: String,
      type: String
    },
    data(){
      return {
        year: new Date().getFullYear()
      }
    }
  }
</script>
<style>
</style>
