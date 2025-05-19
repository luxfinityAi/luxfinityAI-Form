<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Formulario Hostelería - LuxfinityAI</title>
  <style>
    body {
      background-color: #0D0A2B;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      margin: 0;
      padding: 2rem;
    }
    h1 {
      color: #CBA135;
      text-align: center;
    }
    .descripcion {
      max-width: 700px;
      margin: 1rem auto 2rem auto;
      background-color: #1E1B3A;
      padding: 1.5rem;
      border-radius: 15px;
      color: #DDD;
      font-size: 1rem;
      line-height: 1.6;
    }
    form {
      max-width: 700px;
      margin: 0 auto;
      background-color: #1E1B3A;
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 0 20px rgba(203, 161, 53, 0.4);
    }
    label {
      display: block;
      margin-bottom: 0.5rem;
      font-weight: bold;
      color: #A188F2;
    }
    input, textarea, select {
      width: 100%;
      padding: 0.8rem;
      margin-bottom: 1.5rem;
      border-radius: 10px;
      border: none;
      background-color: #2A2549;
      color: white;
    }
    input[type="checkbox"],
    input[type="radio"] {
      width: auto;
      margin-right: 0.5rem;
    }
    .form-section {
      margin-bottom: 2rem;
    }
    .cta-final {
      text-align: center;
      color: #CBA135;
      font-weight: bold;
      margin-bottom: 1.5rem;
      font-size: 1.1rem;
    }
    button {
      background-color: #CBA135;
      color: black;
      padding: 1rem 2rem;
      font-size: 1.1rem;
      border: none;
      border-radius: 15px;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background-color: #f0c75e;
    }
  </style>
</head>
<body>
  <h1>¿Te gustaría automatizar tu restaurante o bar?</h1>
  <div class="descripcion">
    📌 <strong>En menos de 2 minutos</strong> descubrirás si tu negocio puede beneficiarse de automatizaciones con inteligencia artificial.<br><br>
    Trabajamos con <strong>restaurantes, bares, pubs y discotecas</strong> que quieren vender más, gastar menos y ofrecer una experiencia inolvidable al cliente.<br><br>
    🚀 <strong>Completa este formulario</strong> y un asesor de <strong>LuxfinityAI</strong> te contactará con una propuesta personalizada.
  </div>
  <form>
    <div class="form-section"><label>Nombre completo</label><input type="text" required></div>
    <div class="form-section"><label>Email de contacto</label><input type="email" required></div>
    <div class="form-section"><label>Número de teléfono</label><input type="tel" required></div>
    <div class="form-section"><label>¿Cuál es el nombre de tu negocio?</label><input type="text" required></div>
    <div class="form-section"><label>¿A qué categoría pertenece tu negocio?</label>
      <label><input type="checkbox"> Restaurante</label>
      <label><input type="checkbox"> Bar</label>
      <label><input type="checkbox"> Pub</label>
      <label><input type="checkbox"> Discoteca</label>
      <label><input type="checkbox"> Otro</label>
    </div>
    <div class="form-section"><label>¿En qué ciudad estás ubicado?</label><input type="text" required></div>
    <div class="form-section"><label>¿Cuántas personas trabajan actualmente en tu negocio?</label>
      <label><input type="radio" name="empleados"> 0-3</label>
      <label><input type="radio" name="empleados"> 4-10</label>
      <label><input type="radio" name="empleados"> 11-20</label>
      <label><input type="radio" name="empleados"> Más de 20</label>
    </div>
    <div class="form-section"><label>¿Usas alguna herramienta digital para gestionar tu negocio?</label>
      <label><input type="checkbox"> No uso nada</label>
      <label><input type="checkbox"> Excel o Google Sheets</label>
      <label><input type="checkbox"> Software específico</label>
    </div>
    <div class="form-section"><label>¿Qué resultados esperas lograr con esta automatización?</label>
      <textarea rows="3" placeholder="Ej: Vender más, ahorrar tiempo, mejorar atención..."></textarea>
    </div>
    <div class="form-section"><label>¿Qué tan urgente es para ti implementar esta solución?</label>
      <select>
        <option>No lo sé</option>
        <option>Lo antes posible</option>
        <option>En 1-2 meses</option>
        <option>Sólo estoy explorando</option>
      </select>
    </div>
    <div class="cta-final">🎯 ¡Da el primer paso hacia un negocio más inteligente!</div>
    <button type="submit">Enviar</button>
  </form>
</body>
</html>
