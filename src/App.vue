<template>
<div class="cover-container d-flex w-100 h-100 p-3 mx-auto flex-column">
  <header class="mb-auto">
    <div>
      <h3 class="float-md-start mb-0">Coinlog</h3>
      <nav class="nav nav-masthead justify-content-center float-md-end">
        <a class="nav-link active" aria-current="page" href="#">Home</a>
        <a class="nav-link" href="#">Features</a>
        <a class="nav-link" href="#">Status</a>
        <a class="nav-link" href="#">Contact</a>
      </nav>
    </div>
  </header>

  <main class="px-3">
    <img src="./assets/coinlog.png" class="hugeicon" alt="Coinlog">
    <br>
    <h1>Coinlog</h1>
    <p class="lead">A different take on personal finance</p>
    <p><span class="badge bg-danger">BETA</span> Coming soon...</p>
    <p><img src="./assets/header.jpg" alt="Coinlog" class="img-fit-to-container"></p>
<!--     <p class="lead">
      <a href="#" class="btn btn-lg btn-secondary fw-bold border-white bg-white">Learn more</a>
    </p> -->
  </main>

  <footer class="mt-auto text-white-50">
    <p><img src="./assets/coinlog.png" class="copyright" alt="Coinlog" /> Coinlog &copy; 2021</p>
  </footer>
</div>




 
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100%;
  width: 100%;
/*   text-align: center;
  color: #D8DEE9; */
}
.progress-bar {
    background-color: #4C566A !important;
}
.hugeicon{
  width: 100px;
  height: 100px;
}
.copyright{
  width: 24px;
  height: 24px;
}

.img-fit-to-container{
  max-height: 100%;
  max-width: 100%;
}
/*
 * Globals
 */


/* Custom default button */
.btn-secondary,
.btn-secondary:hover,
.btn-secondary:focus {
  color: #333;
  text-shadow: none; /* Prevent inheritance from `body` */
}


/*
 * Base structure
 */

body {
  text-shadow: 0 .05rem .1rem rgba(0, 0, 0, .5);
  box-shadow: inset 0 0 5rem rgba(0, 0, 0, .5);
}

.cover-container {
  max-width: 84em;
}


/*
 * Header
 */

.nav-masthead .nav-link {
  padding: .25rem 0;
  font-weight: 700;
  color: rgba(255, 255, 255, .5);
  background-color: transparent;
  border-bottom: .25rem solid transparent;
}

.nav-masthead .nav-link:hover,
.nav-masthead .nav-link:focus {
  border-bottom-color: rgba(255, 255, 255, .25);
}

.nav-masthead .nav-link + .nav-link {
  margin-left: 1rem;
}

.nav-masthead .active {
  color: #fff;
  border-bottom-color: #fff;
}

</style>
