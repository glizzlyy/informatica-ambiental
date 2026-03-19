<style>
:root{
  --bg-dark:#020617;
  --text-main:#ffffff;
  --text-muted:#94a3b8;
  --primary:#38bdf8;
  --glass:rgba(255,255,255,0.03);
  --glass-border:rgba(255,255,255,0.08);
}

/* Evita límite de Markdown */
.markdown-body{
  max-width:100% !important;
  width:100% !important;
}

/* ===== BODY ===== */
body{
  font-family:'Inter',sans-serif;
  background: radial-gradient(circle at top left,#1e293b,#020617 50%);
  color:var(--text-main);
  margin:0;
}

/* ===== SIDEBAR ===== */
.sidebar{
  width:280px;
  height:100vh;
  position:fixed;
  top:0;
  left:0;
  background:rgba(2,6,23,0.9);
  backdrop-filter:blur(15px);
  border-right:1px solid var(--glass-border);
  padding:40px 20px;
  display:flex;
  flex-direction:column;
}

.sidebar h2{
  font-size:12px;
  letter-spacing:3px;
  text-align:center;
  margin-bottom:30px;
  color:white;
}

.sidebar a{
  font-size:14px;
  color:var(--text-muted);
  text-decoration:none;
  padding:12px 16px;
  margin-bottom:6px;
  border-radius:10px;
  transition:0.3s;
}

.sidebar a:hover{
  background:rgba(56,189,248,0.1);
  color:white;
  transform:translateX(5px);
}

/* ===== CONTENIDO CENTRADO ===== */
.contenido{
  max-width:1100px;
  margin-left:320px;  /* espacio del sidebar */
  margin-right:40px;  /* margen derecho equilibrado */
  padding:100px 40px 80px;
  display:flex;
  flex-direction:column;
  gap:35px;
}

/* Tarjetas centradas */
section{
  background:var(--glass);
  padding:40px;
  border-radius:25px;
  border:1px solid var(--glass-border);
  max-width:900px;
  margin:0 auto;
}

/* Texto */
section p, section ul{
  color:var(--text-muted);
  line-height:1.7;
}

/* Títulos */
h1{
  font-size:60px;
  font-weight:800;
  margin-left:10px;
}

h2{
  font-size:28px;
  margin-bottom:15px;
}

/* Imagen */
img{
  width:100%;
  max-width:800px;
  display:block;
  margin:20px auto;
  border-radius:16px;
}

ul{
  padding-left:20px;
}

ul li{
  margin-bottom:8px;
}
</style>

<nav class="sidebar">
<h2>ÍNDICE</h2>
<a href="index.md">Inicio</a>
<a href="contaminacion.md">Contaminación ambiental</a>
<a href="residuos.md">Residuos informáticos</a>
<a href="obsolescencia.md">Obsolescencia programada</a>
<a href="informatica-ecologica.md">Informática ecológica</a>
</nav>

<main class="contenido">

<h1>♻️ Residuos Informáticos</h1>

<section>
<img src="img/residuos.jpg" alt="Residuos Informáticos">

<p>
Los <strong>residuos informáticos</strong> son todos los dispositivos electrónicos como ordenadores, móviles, tablets o impresoras que han dejado de usarse y que necesitan ser reciclados correctamente. Su manejo adecuado es crucial para proteger el medio ambiente y la salud humana.
</p>
</section>

<section>
<h2>Problema ambiental</h2>

<p>
Muchos dispositivos contienen materiales peligrosos como plomo, mercurio, cadmio, arsénico y retardantes de llama que pueden filtrarse al suelo y al agua si se desechan incorrectamente. Además, los plásticos y microcomponentes tardan siglos en degradarse.
</p>

<ul>
<li><strong>Contaminación por metales pesados:</strong> Plomo, mercurio y cadmio presentes en componentes electrónicos contaminan el suelo y agua.</li>
<li><strong>Plásticos y retardantes de llama:</strong> Difíciles de degradar, afectan a la fauna y flora.</li>
<li><strong>Impacto energético:</strong> La producción de nuevos dispositivos requiere gran cantidad de recursos y electricidad.</li>
</ul>
</section>

<section>
<h2>Soluciones</h2>

<p>
Para reducir el impacto de los residuos electrónicos es fundamental:
</p>

<ul>
<li>Reciclar dispositivos correctamente en puntos autorizados.</li>
<li>Prolongar la vida útil mediante reparaciones o actualizaciones.</li>
<li>Optar por productos certificados como ecológicos o de bajo consumo.</li>
<li>Evitar la compra innecesaria de equipos electrónicos y fomentar la reutilización.</li>
</ul>
</section>

<section>
<h2>Consecuencias</h2>

<p>
El manejo inadecuado de los residuos informáticos provoca contaminación del aire, suelo y agua, afectando la salud de los seres humanos y la biodiversidad. La exposición prolongada a metales pesados puede causar problemas respiratorios, neurológicos y daños a órganos vitales.
</p>

<p>
Concienciarse sobre el reciclaje y la eficiencia energética es clave para proteger nuestro planeta y garantizar un futuro sostenible.
</p>
</section>

</main>
