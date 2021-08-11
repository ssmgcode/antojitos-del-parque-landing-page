<script lang="ts">
  const goToFirstSection = () => {
    document
      .getElementsByTagName('section')[1]
      ?.scrollIntoView({ behavior: 'smooth' })
  }
</script>

<section>
  <div class="container">
    <div class="text">
      <h4>Bienvenido a</h4>
      <h1>Antojitos del Parque</h1>
      <button class="button" on:click={goToFirstSection}>Conócenos</button>
    </div>
    <div class="spacer" />
    <img src="/images/logo.svg" alt="Antojitos del Parque" />
  </div>
</section>

<style>
  .container {
    display: flex;
    flex-direction: column-reverse;
  }

  .spacer {
    width: 50px;
    height: 30px;
  }

  .text {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  h4 {
    color: #959da5;
    font-size: 16px;
    line-height: 20px;
    margin: 0;
  }

  h1 {
    font-weight: 800;
    font-size: 3.2em;
    text-align: center;
    margin: 0;
    margin-bottom: 35px;
  }

  img {
    width: 14em;
    filter: drop-shadow(0 7px 5px rgba(0, 0, 0, 0.2));
  }

  @media screen and (min-width: 768px) {
    .container {
      flex-direction: row;
      flex: 0 1;
    }

    img {
      width: 50%;
      max-width: 250px;
    }

    .text {
      align-items: flex-start;
    }

    h4 {
      font-size: 20px;
      line-height: 24px;
    }

    h1 {
      font-size: 72px;
      line-height: 76px;
      text-align: left;
    }
  }
</style>
