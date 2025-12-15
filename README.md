
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Catálogo de Servicios</title>
  <link rel="stylesheet" href="style.css">
  .{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', system-ui, sans-serif;
}

body {
  background: #f4f7fb;
  color: #222;
}

/* HERO */
.hero {
  background: linear-gradient(135deg, #6a5cff, #8f8bff);
  color: white;
  text-align: center;
  padding: 70px 20px;
}

.hero h1 {
  font-size: 2.4rem;
  margin-bottom: 12px;
  font-weight: 700;
}

.hero p {
  font-size: 1.05rem;
  margin-bottom: 30px;
  opacity: 0.95;
}

.btn-primary {
  background: white;
  color: #6a5cff;
  padding: 15px 34px;
  border-radius: 35px;
  text-decoration: none;
  font-weight: 700;
  box-shadow: 0 10px 25px rgba(0,0,0,0.15);
  transition: transform 0.2s, box-shadow 0.2s;
}

.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 14px 30px rgba(0,0,0,0.25);
}

/* INFO */
.info {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 18px;
  padding: 35px 20px;
}

.info-box {
  background: white;
  padding: 18px 24px;
  border-radius: 18px;
  box-shadow: 0 6px 18px rgba(0,0,0,0.08);
  font-weight: 600;
}

/* SERVICES */
.services {
  padding: 50px 20px;
}

.services h2 {
  text-align: center;
  margin-bottom: 35px;
  font-size: 2rem;
  font-weight: 700;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 25px;
}

.card {
  background: white;
  border-radius: 22px;
  padding: 28px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.25s, box-shadow 0.25s;
}

.card:hover {
  transform: translateY(-6px);
  box-shadow: 0 16px 35px rgba(0,0,0,0.15);
}

.card h3 {
  font-size: 1.4rem;
  margin-bottom: 8px;
}

.card p {
  font-size: 0.95rem;
  margin-bottom: 18px;
  color: #555;
}

.price {
  display: inline-block;
  background: #f0f2ff;
  color: #6a5cff;
  padding: 10px 18px;
  border-radius: 30px;
  font-size: 1.3rem;
  font-weight: 700;
  margin-bottom: 18px;
}

/* BOTÓN WHATSAPP */
.btn {
  display: inline-block;
  background: linear-gradient(135deg, #25d366, #1ebe57);
  color: white;
  padding: 14px 26px;
  border-radius: 30px;
  text-decoration: none;
  font-weight: 700;
  box-shadow: 0 8px 20px rgba(37, 211, 102, 0.35);
  transition: transform 0.2s, box-shadow 0.2s;
}

.btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 28px rgba(37, 211, 102, 0.45);
}

/* FOOTER */
footer {
  text-align: center;
  padding: 25px;
  font-size: 0.85rem;
  background: #eef1f8;
  color: #555;
}
</head>
<body>

  <!-- HEADER -->
  <header class="hero">
    <h1>Nombre del Negocio</h1>
    <p>Servicios profesionales · Precios claros · Reservá fácil</p>
    <a href="#servicios" class="btn-primary">Ver servicios</a>
  </header>

  <!-- INFO -->
  <section class="info">
    <div class="info-box">📍 Atención por turno</div>
    <div class="info-box">💬 Reserva directa por WhatsApp</div>
    <div class="info-box">⏱️ Respuesta rápida</div>
  </section>

  <!-- SERVICIOS -->
  <section id="servicios" class="services">
    <h2>Servicios</h2>

    <div class="cards">

      <div class="card">
        <h3>Servicio 1</h3>
        <p>Duración: 60 min</p>
        <span class="price">$8.000</span>
        <a class="btn"
           href="https://wa.me/549XXXXXXXXXX?text=Hola!%20Quiero%20reservar%20el%20Servicio%201">
           Reservar por WhatsApp
        </a>
      </div>

      <div class="card">
        <h3>Servicio 2</h3>
        <p>Duración: 45 min</p>
        <span class="price">$6.500</span>
        <a class="btn"
           href="https://wa.me/549XXXXXXXXXX?text=Hola!%20Quiero%20reservar%20el%20Servicio%202">
           Reservar por WhatsApp
        </a>
      </div>

      <div class="card">
        <h3>Servicio 3</h3>
        <p>Duración: 30 min</p>
        <span class="price">$5.000</span>
        <a class="btn"
           href="https://wa.me/549XXXXXXXXXX?text=Hola!%20Quiero%20reservar%20el%20Servicio%203">
           Reservar por WhatsApp
        </a>
      </div>

    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>Contacto y reservas vía WhatsApp</p>
  </footer>

</body>
</html>
