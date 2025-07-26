<div align="center">

# Sistema Hospitalario 

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

**Vladmir Diaz Contreras**  
**Santiago Andres Quiñonez Sosa**

&nbsp;  
&nbsp;  
 
**S1**  
&nbsp;  
&nbsp;  
&nbsp;  

**PEDRO FELIPE GÓMEZ BONILLA**  

&nbsp;  
&nbsp;  
&nbsp;  

**CAMPUSLANDS**  
**Cajasan**  
**RUTA NODEJS**  
**BUCARAMANGA**  
**CAJASAN**
**2025**
<br>
</div>
<br>

#

<br>
<br>

## Tabla de Contenidos

- [Introducción](#introducción)
- [Caso de Estudio](#caso-de-estudio)
- [Planificación](#planificación)
- [Construcción del Modelo Conceptual](#construcción-del-modelo-conceptual)
  - [Descripción](#descripción)
  - [Gráfica](#gráfica)
  - [Descripción Técnica](#descripción-técnica)
- [Construcción del Modelo Lógico](#construcción-del-modelo-lógico)
  - [Descripción](#descripción-1)
  - [Gráfica](#gráfica-1)
  - [Descripción Técnica](#descripción-técnica-1)
- [Normalización del Modelo Lógico](#normalización-del-modelo-lógico)
  - [Primera Forma Normal (1FN)](#primera-forma-normal-1fn)
    - [Descripción](#descripción-2)
    - [Gráfica](#gráfica-2)
    - [Descripción Técnica](#descripción-técnica-2)
  - [Segunda Forma Normal (2FN)](#segunda-forma-normal-2fn)
    - [Descripción](#descripción-3)
    - [Gráfica](#gráfica-3)
    - [Descripción Técnica](#descripción-técnica-3)
  - [Tercera Forma Normal (3FN)](#tercera-forma-normal-3fn)
    - [Descripción](#descripción-4)
    - [Gráfica](#gráfica-4)
    - [Descripción Técnica](#descripción-técnica-4)
- [Construcción del Modelo Físico](#construcción-del-modelo-físico)
  - [Descripción](#descripción-5)
  - [Código](#código)
  - [Descripción Técnica](#descripción-técnica-5)
- [Diagrama E-R](#diagrama-e-r)
  - [Descripción](#descripción-6)
  - [Gráfica](#gráfica-5)
  - [Descripción Técnica](#descripción-técnica-6)
- [Tablas](#tablas)
  - [Descripción](#descripción-7)
  - [Gráfica](#gráfica-6)
  - [Descripción Técnica](#descripción-técnica-7)
- [Relaciones entre Tablas](#relaciones-entre-tablas)
  - [Descripción](#descripción-8)
  - [Gráfica](#gráfica-7)
  - [Descripción Técnica](#descripción-técnica-8)
- [Inserción de Datos](#inserción-de-datos)
  - [Descripción](#descripción-9)
  - [Gráfica](#gráfica-8)
  - [Descripción Técnica](#descripción-técnica-9)
- [Referencias](#referencias)
<h2 id="construcción-del-modelo-conceptual">Construcción del Modelo Conceptual</h2>

<h3 id="descripción">Descripción</h3>

<h4>Entidades y atributos principales:</h4>

<ol>
  <li><strong>Hospital</strong>
    <ul>
      <li><code>_id</code> (UUID)</li>
      <li><code>nombre</code></li>
      <li><code>dirección</code></li>
      <li><code>teléfono</code></li>
      <li><code>áreas</code> (lista de cadenas de texto)</li>
    </ul>
  </li>

  <li><strong>Médico</strong>
    <ul>
      <li><code>_id</code> (UUID)</li>
      <li><code>nombre</code></li>
      <li><code>hospital_id</code> (referencia a Hospital)</li>
      <li><code>área</code></li>
      <li><code>especialidad</code></li>
      <li><code>registro_médico</code></li>
      <li><code>obligaciones</code> (lista de cadenas de texto)</li>
    </ul>
    <p><strong>Relaciones:</strong> Atiende pacientes (vía historia_clínica)</p>
  </li>

  <li><strong>Administrativo</strong>
    <ul>
      <li><code>_id</code> (UUID)</li>
      <li><code>nombre</code></li>
      <li><code>cargo</code></li>
      <li><code>hospital_id</code> (referencia a Hospital)</li>
      <li><code>obligaciones</code></li>
    </ul>
  </li>

  <li><strong>Paciente</strong>
    <ul>
      <li><code>_id</code> (UUID)</li>
      <li><code>nombre</code></li>
      <li><code>tipo_documento</code></li>
      <li><code>numero_documento</code></li>
      <li><code>fecha_nacimiento</code></li>
      <li><code>dirección</code></li>
      <li><code>teléfono</code></li>
      <li><code>eps_id</code> (UUID)</li>
      <li><code>obligaciones</code></li>
      <li><code>historia_clínica</code> (lista de subdocumentos)</li>
    </ul>
  </li>

  <li><strong>Historia Clínica</strong> (subdocumento de Paciente)
    <ul>
      <li><code>fecha</code></li>
      <li><code>motivo</code></li>
      <li><code>diagnóstico</code></li>
      <li><code>medico_id</code> (referencia a Médico)</li>
      <li><code>tratamiento</code></li>
    </ul>
  </li>

  <li><strong>EPS</strong>
    <ul>
      <li><code>_id</code> (UUID)</li>
      <li><code>nombre</code> (String)</li>
      <li><code>responsabilidades</code></li>
      <li><code>Director_EPS</code> (subdocumento)</li>
    </ul>
  </li>

  <li><strong>Director_EPS</strong>
    <ul>
      <li><code>_id</code> (UUID)</li>
      <li><code>nombre</code> (String)</li>
      <li><code>responsabilidades</code></li>
    </ul>
  </li>
</ol>

<h3 id="gráfica">Gráfica</h3>

<div align="center">
  <img src="./salud.drawio (1).png" alt="Modelo Conceptual" width="800px">
  <br><br>
  <a href="https://drive.google.com/file/d/1TrpyUwY_rDEoA1gYqghtMEs9JYpaQpoM/view?usp=sharing" target="_blank">🔗 Ver en Draw.io</a>
</div>

<h3 id="descripción-técnica">Descripción Técnica</h3>

<p>
  El modelo conceptual del sistema hospitalario se define a través de entidades clave y sus relaciones, sin tener en cuenta el almacenamiento físico.
  Las principales entidades son: <strong>Hospital</strong>, <strong>Médico</strong>, <strong>Administrativo</strong>, <strong>Paciente</strong>,
  <strong>Historia Clínica</strong>, <strong>EPS</strong> y <strong>Director de EPS</strong>.
</p>

<p>
  Cada hospital tiene atributos como <code>_id</code>, nombre, dirección, teléfono y lista de áreas.
  Los hospitales se relacionan con médicos y personal administrativo mediante el campo <code>hospital_id</code>.
</p>

<p>
  Los médicos se caracterizan por su identificación única, nombre, especialidad, área de trabajo, obligaciones,
  y están conectados a los pacientes por medio del subdocumento historia clínica.
</p>

<p>
  El personal administrativo posee nombre, cargo, hospital asociado y una lista de obligaciones.
</p>

<p>
  Los pacientes incluyen datos personales, su EPS asociada (<code>eps_id</code>), obligaciones,
  y una colección de historias clínicas que representan la atención médica recibida,
  con información como fecha, motivo, diagnóstico, médico tratante y tratamiento.
</p>

<p>
  La entidad <strong>EPS</strong> contiene información propia y un subdocumento llamado <strong>Director_EPS</strong>,
  el cual guarda datos del director junto con sus responsabilidades.
  Las EPS pueden estar asociadas a múltiples pacientes.
</p>

<p>
  Este modelo permite visualizar un sistema hospitalario completo, distribuido en diferentes capas administrativas y clínicas,
  con relaciones estructuradas entre los actores del sistema de salud.
</p>
