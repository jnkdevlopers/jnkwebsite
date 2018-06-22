<template>
   <div id="content">
    <!-- Section / Home -->
    <section id="home" class="section cover text-xs-center">

        <div class="container container-sm fullheight">

            <!-- BG Side -->
            <div class="bg-side bg-left">
                <img src="../assets/img/items/docs.png" alt="" class="animated" data-animation="slideInLeft">
            </div>
            <!-- BG Side -->
            <div class="bg-side bg-right">
                <img src="../assets/img/items/ipad.png" alt="" class="animated" data-animation="bounceInDown" data-animation-delay="600">
                <img   src="../assets/img/items/plant2.png" alt="" class="animated" data-animation="slideInRight" data-animation-delay="300" >
            </div>

            <!-- Content -->
            <div class="v-center pt-90 pb-90">
                <h1 class="display-3">Lets Make It Awesome!</h1>
                <p class="lead text-muted">Web development | Android development | Tutorials <br> Games | Computer Assembling | Tech Talks <br>Online Support</p>
                <div class="btn-group" data-local-scroll>
                    <a href="about.html" class="btn btn-primary btn-lg">About us</a>
                    <a href="services.html" class="btn btn-secondary btn-lg">Our services</a>
                </div>
            </div>

        </div>

    </section>

</div>
</template>
<script>
export default {
  name: 'About Us',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
