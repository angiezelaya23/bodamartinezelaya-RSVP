<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>RSVP Boda</title>
  <style>
    body {
      font-family: 'Brush Script MT', cursive;
      background: url('https://www.transparenttextures.com/patterns/white-velvet.png');
      background-color: #ffffff;
      color: #333;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 2em;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.5em;
    }

    .invitation-link {
      margin: 1.5em 0;
    }

    .invitation-link a {
      font-size: 1.2em;
      text-decoration: underline;
      color: #555;
    }

    form {
      margin-top: 2em;
    }

    .option {
      font-size: 1.5em;
      margin: 1em 0;
    }

    input[type="checkbox"] {
      transform: scale(1.5);
      margin-right: 10px;
    }

    footer {
      background-color: #000;
      color: white;
      padding: 2em 0;
      margin-top: 3em;
      font-size: 1.2em;
    }

    button {
      font-size: 1.2em;
      padding: 0.5em 1em;
      margin-top: 1em;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #555;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>¡Estás invitado a nuestra boda!</h1>

    <div class="invitation-link">
      <p><a href="TU_ARCHIVO_DE_INVITACION.pdf" target="_blank">Haz clic aquí para ver la invitación (PDF)</a></p>
    </div>

    <form>
      <div class="option">
        <label><input type="checkbox" name="rsvp" value="asistire"> Sí, asistiré</label>
      </div>
      <div class="option">
        <label><input type="checkbox" name="rsvp" value="talvez"> Tal vez, pendiente a confirmación <br>(fecha máx. 12 de septiembre)</label>
      </div>
      <div class="option">
        <label><input type="checkbox" name="rsvp" value="noasistire"> Lastimosamente, no podré asistir</label>
      </div>

      <button type="submit">Enviar RSVP</button>
    </form>
  </div>

  <footer>
    Dirección: [Aquí va la dirección del evento]
  </footer>
</body>
</html>
