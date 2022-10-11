
<!--Seccion Javascript    ----------------------------------->
<script setup>
let usuario = 'Carolina';
let edad = '23';

let impares = [1, 3, 5, 7, 9, 11, 13, 15, 17, 19];

</script>



<!-- seccion HTML aqui se mete todo lo html ---------->
<template>

<h1>Bienvenido a mi pagina VUE</h1>

<h2>Hola! {{ usuario }}, ¿Cómo estás hoy?</h2>
<h3>Tienes {{edad}} años</h3>

<h4 v-if="edad>=18">Y eres mayor de edad</h4>
<h4 v-if="edad<=18">Y eres menor de edad</h4>

<ul>
      <li v-for="num in impares"> <h2>{{num}}</h2></li>
</ul>


</template>

<!-- seccion CSS-------------------------------------------->
<style>

h1 {
color: crimson;
}

li{
color: blue;
font-size: small;
}
</style>






















<!--ORIGINAL-->


<!-- <script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style> -->



