<script>
  import MainSection from './sections/MainSection.svelte'
</script>

<div id="app">
  <div class="navbar"><nav>Hola</nav></div>
  <main>
    <MainSection />
  </main>
</div>

<!-- SECTIONS
  - Ubicación
  - Horario
  - Menu
  - Redes sociales
 -->
<style>
  #app {
    font-family: 'Inter';
    display: grid;
    grid-template:
      'navbar'
      'main';
  }

  :global(.section-title) {
    font-family: 'Yanone Kaffeesatz';
    font-weight: 700;
    font-size: 2.5rem;
  }
</style>
