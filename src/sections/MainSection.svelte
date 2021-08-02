<div class="section">
  <div class="container">
    <div class="title">
      <h1>Antojitos del Parque</h1>
      <button class="button">Conócenos</button>
    </div>
    <div class="spacer" />
    <img src="/images/logo.svg" alt="Antojitos del Parque" />
  </div>
</div>

<style>
  .section {
    padding-top: 50px;
    padding-bottom: 50px;
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  .spacer {
    width: 50px;
    height: 50px;
  }

  .title {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  @media screen and (min-width: 768px) {
    .container {
      flex-direction: row;
    }

    .title {
      align-items: flex-start;
    }
  }

  h1 {
    font-family: 'Yanone Kaffeesatz';
    font-weight: 700;
    font-size: 5em;
    text-align: center;
    margin: 0;
    margin-bottom: 35px;
  }

  img {
    width: 15em;
  }
</style>
