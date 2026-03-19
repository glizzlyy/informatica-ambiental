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
}

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

.contenido{
  max-width:1400px;
  margin-left:320px;
  margin-right:40px;
  padding:100px 40px 80px;
  display:flex;
  flex-direction:column;
  gap:35px;
}

section{
  background:var(--glass);
  padding:40px;
  border-radius:25px;
  border:1px solid var(--glass-border);
  max-width:1100px; /* MÁS ANCHO */
  margin:0 auto;
}

section p, section ul{
  color:var(--text-muted);
  line-height:1.7;
}

h1{
  font-size:60px;
  font-weight:800;
  margin-left:10px;
}

h2{
  font-size:28px;
  margin-bottom:15px;
}

img{
  width:100%;
  max-width:900px;
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

- [Inicio](index.md)
- [Contaminación ambiental](contaminacion.md)
- [Residuos informáticos](residuos.md)
- [Obsolescencia programada](obsolescencia.md)
- [Informática ecológica](informatica-ecologica.md)

</nav>

<main class="contenido">

# 🌍 Contaminación Ambiental

<section>

![Contaminación Ambiental](img/contaminacion.jpg)

La contaminación ambiental es la introducción de sustancias o energía que provocan efectos negativos en el medio ambiente y la salud de los seres humanos.

Este problema afecta al aire, al agua y al suelo. En gran parte es causado por las actividades humanas como las fábricas, el transporte, el uso de combustibles fósiles y la mala gestión de los residuos.

Existen distintos tipos de contaminación: atmosférica, hídrica, del suelo, lumínica y sonora, cada una con efectos específicos sobre los ecosistemas y la vida cotidiana de las personas.

</section>

<section>

## Impacto de la informática

La producción de dispositivos electrónicos requiere energía y recursos naturales, generando emisiones contaminantes. Además, los centros de datos consumen mucha electricidad para almacenar información y mantener funcionando internet.

Cuando los ordenadores, móviles o tablets dejan de usarse y no se reciclan correctamente, se convierten en residuos electrónicos que pueden contaminar el medio ambiente debido a los materiales tóxicos que contienen.

- **Contaminación por metales pesados:** Plomo, mercurio y cadmio pueden filtrarse al suelo y agua.  
- **Contaminación energética:** Alto consumo eléctrico de centros de datos.  
- **Plásticos y químicos:** Difíciles de degradar y dañinos para ecosistemas.

Para reducir este impacto, es importante reciclar los dispositivos, prolongar su vida útil y elegir productos ecológicos.

</section>

<section>

## Consecuencias

- Contaminación del aire  
- Contaminación del suelo  
- Daños en los ecosistemas  
- Impacto en la salud humana  
- Pérdida de biodiversidad  

La acumulación de residuos y la contaminación afectan a los ecosistemas naturales, provocando la desaparición de especies y problemas de salud en las personas.

Concienciarse y aplicar buenas prácticas es clave para proteger el planeta.

</section>

</main>
