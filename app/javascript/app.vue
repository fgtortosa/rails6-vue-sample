<template>
  <div id="app">
    <section class="hero is-primary">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Visitas
          </h1>
          <h2 class="subtitle">
            Interface para controlar las visitas en la aplicación Rails
          </h2>
        </div>
      </div>
    </section>
    <div class="content has-text-centered has-padding-35">
      <h2>
        {{message}}
      </h2>
    </div>
    <footer class="footer">
      <div class="content has-text-centered has-padding-top-5">
        <p>
          <strong>Bulma</strong> by <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
          is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Di hola a Vue .."
    }
  }
}
</script>

<style scoped>
</style>
