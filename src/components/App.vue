<template>
  <div id="app">
    <section class="hero is-primary is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <img src="../assets/images/logo.png" height="100" alt="">
          <h1 class="title">
            Homie
          </h1>
          <h2 class="subtitle">
            A lightweight MQTT convention for the IoT
          </h2>
          
          <div class="box">
            <span class="tag is-primary">homie/</span>
            <span class="tag is-success">my-weather-device/</span>
            <span class="tag is-dark">$online</span>
            <span style="color: #000;">→</span>
            <span class="tag is-black">true</span>
            
            <br><br>
            
            <span class="tag is-primary">homie/</span>
            <span class="tag is-success">my-weather-device/</span>
            <span class="tag is-warning">my-temperature-node/</span>
            <span class="tag is-dark">degrees</span>
            <span style="color: #000;">→</span>
            <span class="tag is-black">27.02</span>
            
            <br><br>
            
            <span class="tag is-primary">homie/</span>
            <span class="tag is-success">my-weather-device/</span>
            <span class="tag is-warning">my-temperature-node/</span>
            <span class="tag is-dark">degrees/$unit</span>
            <span style="color: #000;">→</span>
            <span class="tag is-black">°C</span>
          </div>
          
          <a href="https://github.com/marvinroger/homie" target="_blank" class="button is-primary is-inverted">
            <span class="icon">
              <i class="fa fa-github"></i>
            </span>
            <span>See on GitHub</span>
          </a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
  }
</script>

<style lang="sass">
  $homiered: #e74c3c
  $primary: $homiered
  $link-visited: $primary
  @import "~bulma"
  
  $fa-font-path: "~font-awesome/fonts"
  @import "~font-awesome/scss/font-awesome.scss"
</style>
