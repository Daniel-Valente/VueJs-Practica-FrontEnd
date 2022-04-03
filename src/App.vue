<template>
  <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #fff3eb;" >
    <div class="container-fluid">
      <router-link class="navbar-brand" to="/" style="color:#FF9AA2">RM Repostería</router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <router-link class="nav-link active" aria-current="page" to="/">Cliente</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/pastelero-home">Pastelero</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  font-weight: bold;
  color: #2c3e50;
}

</style>

<script>

export default ({
  name: 'App',
  components: {
  },
})
</script>

