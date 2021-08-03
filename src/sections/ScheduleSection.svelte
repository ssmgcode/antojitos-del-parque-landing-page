<section>
  <div class="texts-container">
    <h3 id="horarios">Horarios</h3>
    <p>
      ¿Te apetece pasar por una merienda, o por un postre nocturno? Te invitamos
      a visitarnos en estos horarios
    </p>
  </div>
  <div class="table-container">
    <table>
      <thead>
        <tr>
          <td>Día</td>
          <td>Hora</td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Lunes</td>
          <td>10:30 AM - 08:30 PM</td>
        </tr>
        <tr>
          <td>Martes</td>
          <td>09:30 AM - 08:30 PM</td>
        </tr>
        <tr>
          <td>Miércoles</td>
          <td>11:30 AM - 08:30 PM</td>
        </tr>
        <tr>
          <td>Jueves</td>
          <td>09:30 AM - 08:30 PM</td>
        </tr>
        <tr>
          <td>Viernes</td>
          <td>09:30 AM - 08:30 PM</td>
        </tr>
        <tr>
          <td>Sábado</td>
          <td>09:30 AM - 09:00 PM</td>
        </tr>
        <tr>
          <td>Domingo</td>
          <td>09:30 AM - 09:00 PM</td>
        </tr>
      </tbody>
    </table>
  </div>
</section>

<style>
  section {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .table-container {
    border-radius: var(--border-radius);
    width: max-content;
    /* margin-left: auto; */
    /* margin-right: auto; */
    border: 1px solid var(--soft-grey-for-borders);
  }

  table {
    border-collapse: collapse;
  }

  thead {
    text-align: center;
    font-weight: 700;
    border-bottom: 1px solid var(--soft-grey-for-borders);
  }

  td {
    padding: 10px 13px;
  }

  tbody > tr > td:nth-last-child(1) {
    text-align: center;
  }

  @media screen and (min-width: 768px) {
    section {
      flex-direction: row;
      justify-content: space-between;
      align-items: flex-start;
    }

    .texts-container {
      flex: 0.75;
    }
  }
</style>
