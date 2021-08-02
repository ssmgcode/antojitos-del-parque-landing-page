<div class="section">
  <div class="container">
    <div class="title">
      <h4>Bienvenido a</h4>
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
    flex-direction: column-reverse;
    align-items: center;
    justify-content: center;
  }

  .spacer {
    width: 50px;
    height: 30px;
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

  h4 {
    color: #959da5;
    font-size: 16px;
    margin: 0;
  }

  h1 {
    font-weight: 800;
    letter-spacing: -0.05em;
    font-size: 3.2em;
    text-align: center;
    margin: 0;
    margin-bottom: 35px;
  }

  img {
    width: 14em;
    filter: drop-shadow(0 7px 5px rgba(0, 0, 0, 0.2));
  }
</style>
