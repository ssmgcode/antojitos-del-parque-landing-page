<script>
  import Footer from './components/Footer.svelte'
  import NavBar from './components/NavBar.svelte'
  import LocationSection from './sections/LocationSection.svelte'
  import MainSection from './sections/MainSection.svelte'
  import MenuSection from './sections/MenuSection.svelte'
  import ScheduleSection from './sections/ScheduleSection.svelte'
  import SocialMediaSection from './sections/SocialMediaSection.svelte'
</script>

<div id="app">
  <NavBar />
  <div class="middle-section">
    <main>
      <MainSection />
      <LocationSection />
      <ScheduleSection />
      <MenuSection />
      <SocialMediaSection />
    </main>
    <Footer />
  </div>
</div>

<style>
  #app {
    font-family: 'Inter';
    height: 100vh;
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: auto 1fr;
    grid-template:
      'navbar'
      'middle-section';
  }

  .middle-section {
    grid-area: middle-section;
    overflow: auto;
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr auto;
    grid-template-areas:
      'main'
      'footer';
  }
</style>
