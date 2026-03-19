<style>
:root{
  --bg-dark:#020617;
  --text-main:#ffffff;
  --text-muted:#94a3b8;
  --primary:#38bdf8;
  --glass:rgba(255,255,255,0.03);
  --glass-border:rgba(255,255,255,0.08);
}

body{
  font-family:'Inter',sans-serif;
  background: radial-gradient(circle at top left,#1e293b,#020617 50%);
  color:var(--text-main);
  margin:0;
  min-height:100vh;
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

/* ===== CONTENIDO ===== */
.contenido{
  max-width:900px;
  margin-left:320px; /* espacio para el sidebar */
  padding:100px 40px 80px;
  display:flex;
  flex-direction:column;
  gap:35px;
}

/* Tarjetas tipo glass */
section{
  background:var(--glass);
  padding:40px;
  border-radius:25px;
  border:1px solid var(--glass-border);
}

/* Texto alineado a la izquierda */
section p, section ul{
  color:var(--text-muted);
  line-height:1.7;
  text-align:left;
}

h1{
  font-size:60px;
  font-weight:800;
  text-align:left;
}

h2{
  font-size:28px;
  margin-bottom:15px;
  text-align:left;
}

img{
  width:100%;
  max-width:650px;
  display:block;
  margin:20px 0;
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

<h1>🌍 Contaminación ambiental</h1>

<section>
<img src="img/contaminacion.jpg" alt="Contaminación">

<p>
La contaminación ambiental es la introducción de sustancias o energía que provocan efectos negativos en el medio ambiente y la salud de los seres humanos.
</p>

<p>
Este problema afecta al aire, al agua y al suelo. En gran parte es causado por las actividades humanas como las fábricas, el transporte, el uso de combustibles fósiles y la mala gestión de los residuos.
</p>

<p>
Existen distintos tipos de contaminación: atmosférica, hídrica, del suelo, lumínica y sonora, cada una con efectos específicos sobre los ecosistemas y la vida cotidiana de las personas.
</p>
</section>

<section>
<h2>Impacto de la informática</h2>

<p>
La producción de dispositivos electrónicos requiere energía y recursos naturales, generando emisiones contaminantes. Además, los centros de datos consumen mucha electricidad para almacenar información y mantener funcionando internet.
</p>

<p>
Cuando los ordenadores, móviles o tablets dejan de usarse y no se reciclan correctamente, se convierten en residuos electrónicos que pueden contaminar el medio ambiente debido a los materiales tóxicos que contienen.
</p>

<ul>
<li><strong>Contaminación por metales pesados:</strong> Plomo, mercurio y cadmio presentes en componentes electrónicos pueden filtrarse al suelo y agua.</li>
<li><strong>Contaminación energética:</strong> Los centros de datos consumen gran cantidad de electricidad, muchas veces generada por combustibles fósiles.</li>
<li><strong>Plásticos y químicos difíciles de degradar:</strong> Retardantes de llama y microplásticos afectan a la fauna y flora cuando no se gestionan correctamente.</li>
</ul>

<p>
Para reducir este impacto, es importante reciclar los dispositivos, prolongar su vida útil mediante reparaciones o actualizaciones, y optar por productos electrónicos certificados como ecológicos o de bajo consumo.
</p>
</section>

<section>
<h2>Consecuencias</h2>

<ul>
<li>Contaminación del aire</li>
<li>Contaminación del suelo</li>
<li>Daños en los ecosistemas</li>
<li>Impacto en la salud humana</li>
<li>Pérdida de biodiversidad</li>
</ul>

<p>
La acumulación de residuos y la contaminación afectan a los ecosistemas naturales, provocando la desaparición de especies y problemas de salud en las personas. La exposición prolongada a metales pesados y químicos presentes en la electrónica puede causar enfermedades respiratorias, problemas neurológicos y daños a órganos vitales.
</p>

<p>
Concienciarse sobre estos problemas y aplicar buenas prácticas de reciclaje y eficiencia energética es clave para proteger nuestro planeta y la salud de las generaciones futuras.
</p>
</section>

</main>
