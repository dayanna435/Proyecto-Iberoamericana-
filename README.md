<h1 align="center">Plataforma Académica Digital para la Educación Universitaria</h1>

<h3>Proyecto de Investigación:</h3>

<p>Es un sistema innovador diseñado para centralizar y mejorar la gestión académica en universidades. Su objetivo es ofrecer una solución digital que facilite la adaptación de los estudiantes, optimice los procesos administrativos y mejore la interacción entre alumnos, docentes y personal universitario.

A diferencia de plataformas tradicionales como Moodle, esta propuesta busca integrar todos los aspectos educativos y administrativos en un solo entorno digital, proporcionando herramientas de orientación académica, recursos de aprendizaje interactivos, seguimiento del progreso estudiantil y comunicación efectiva entre la comunidad universitaria.</p>

<h3>Integrantes:</h3>
  <ol>
    <li><strong>Integrante 1:</strong> Dayanna Malagón</li>
    <li><strong>Integrante 2:</strong> Samuel Rivera</li>
  </ol>

<p align="center">
  <a href="https://github.com/dayanna435/Proyecto-Iberoamericana-/issues">
    <img src="https://img.shields.io/github/issues/dayanna435/Proyecto-Iberoamericana-" alt="Issues">
  </a>
  <a href="https://github.com/dayanna435/Proyecto-Iberoamericana-/stargazers">
    <img src="https://img.shields.io/github/stars/dayanna435/Proyecto-Iberoamericana-" alt="Stars">
  </a>
  <a href="https://github.com/dayanna435/Proyecto-Iberoamericana-/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/dayanna435/Proyecto-Iberoamericana-" alt="License">
  </a>
</p>
<!-- Indice -->
<details>
  <summary>Índice:</summary>
  <ol>
    <li><a href="#introduccion">📌 Introducción.</a></li>
    <li><a href="#objetivos">🎯 Contexto y Objetivos.</a></li>
    <li><a href="#requisitos">📋 Requisitos.</a></li>
    <li><a href="#metodologia">🔍 Metodología de desarrollo.</a></li>
    <li><a href="#arquitectura">🏗️ Arquitectura del Proyecto.</a></li>
    <li><a href="#diagramas">📐 Diagramas UML.</a></li>
    <li><a href="#conclusion">📝 Conclusiones.</a></li>
  </ol>
</details>
<!-- Introducción -->
<h2 id="introduccion">📌 Introducción</h2>
<h3>Identificación del problema:</h3>
<p>La Corporación Universitaria Iberoamericana actualmente utiliza una plataforma educativa basada en Moodle como su campus virtual oficial. Aunque Moodle ha sido una herramienta útil y ampliamente adoptada en el ámbito educativo, su implementación en la universidad presenta importantes desafíos que limitan su eficacia como espacio integral de enseñanza y aprendizaje.

Entre los principales problemas detectados se encuentran: una interfaz de usuario poco atractiva y no adaptada a las expectativas actuales de estudiantes y docentes, escasa compatibilidad y problemas con dispositivos móviles, y una baja integración con herramientas tecnológicas emergentes, tales como sistemas de videoconferencia, aplicaciones de colaboración en tiempo real o analíticas de aprendizaje. Además, muchas de las metodologías pedagógicas modernas, como el aprendizaje activo, personalizado o basado en competencias, no están siendo plenamente aprovechadas debido a las limitaciones en el diseño y uso actual de la plataforma.</p>

<p align="center">
  <img src="./docs/ux-ui/aulavirtual.PNG" alt="Image 1" width="50%">
</p>

<p>A nivel técnico, la personalización y el mantenimiento del sistema Moodle se han vuelto complejos, dificultando su evolución y adaptación a nuevas demandas institucionales. Estas deficiencias han derivado en una experiencia digital fragmentada, una baja motivación por parte de los usuarios, y el uso de plataformas externas no oficiales para complementar procesos académicos y administrativos.

En este contexto, es urgente repensar y modernizar el campus virtual de la universidad mediante tecnologías más actuales, interfaces más amigables e intuitivas, y enfoques pedagógicos centrados en el estudiante. El objetivo es construir un entorno virtual más eficiente, accesible y flexible, que fortalezca los procesos de enseñanza-aprendizaje y contribuya a una educación superior más innovadora y de calidad.</p>
<!-- Objetivos -->
<h2 id="objetivos">🎯 Contexto y Objetivos:</h2>
<ol>
    <li><strong>Nombre del problema: </strong>Obsolescencia tecnológica y pedagógica del campus virtual basado en Moodle en la Universidad Iberoamericana</li>
    <li><strong>Descripción: </strong>El campus virtual actual, desarrollado sobre la plataforma Moodle, presenta una serie de limitaciones tanto técnicas como pedagógicas. Estas limitaciones incluyen una interfaz desactualizada, baja adaptabilidad a dispositivos móviles, dificultad de integración con herramientas modernas y una escasa implementación de metodologías educativas actuales. Estas deficiencias afectan negativamente la experiencia de estudiantes, docentes y personal administrativo, generando desmotivación, baja adopción y dependencia de soluciones externas.</li>
    <li><strong>Areas afectadas:</strong><br>
        <ul>
            <li>Área Académica (estudiantes y docentes)</li>
            <li>Área Administrativa</li>
            <li>Tecnologías de la Información (TI)</li>
            <li>Dirección de Innovación Educativa o equivalente</li>
        </ul>
    </li>
    <li><strong>Impacto:</strong><br>
        <ul>
            <li>Disminución en la calidad del proceso de enseñanza-aprendizaje</li>
            <li>Baja participación y motivación estudiantil</li>
            <li>Carga operativa y técnica adicional para docentes y personal TI</li>
            <li>Pérdida de eficiencia institucional</li>
            <li>Uso fragmentado de múltiples plataformas externas no oficiales</li>
        </ul>
    </li>
    <li><strong>Causas principales:</strong><br>
        <ul>
            <li>Uso de una versión antigua de Moodle sin actualizaciones relevantes</li>
            <li>Falta de personalización y adaptación a las necesidades actuales</li>
            <li>Escasa integración con nuevas tecnologías educativas</li>
            <li>Limitada formación docente en metodologías activas aplicadas al entorno virtual</li>
            <li>Interfaz poco amigable para los usuarios</li>
        </ul>
    </li>
    <li><strong>Consecuencias:</strong><br>
        <ul>
            <li>Experiencia digital poco satisfactoria para los estudiantes</li>
            <li>Bajo aprovechamiento del entorno virtual como herramienta de aprendizaje</li>
            <li>Dificultad en el seguimiento del rendimiento académico</li>
            <li>Fragmentación de los procesos académicos y administrativos</li>
        </ul>
    </li>
    <li><strong>Posible solución: </strong> Desarrollo de un nuevo campus virtual propio, moderno, basado en tecnologías actualizadas, con una interfaz amigable, adaptable a distintos dispositivos y centrado en la implementación de metodologías pedagógicas activas y colaborativas. Este nuevo entorno debe facilitar la integración con herramientas externas, mejorar la experiencia del usuario y fortalecer los procesos académicos y administrativos</li>
</ol>
<h3>Objetivo principal:</h3>
<p>Diseñar y desarrollar un nuevo campus virtual para la Universidad [Nombre], que modernice la plataforma actual mediante tecnologías más eficientes, interfaces accesibles y metodologías pedagógicas innovadoras, con el fin de mejorar la experiencia de aprendizaje, enseñanza y gestión institucional.</p>
<h3>Objetivos específicos:</h3>
<ol>
    <li>Analizar las necesidades y expectativas de los distintos usuarios del campus virtual (estudiantes, docentes y administrativos).</li>
    <li>Evaluar las limitaciones técnicas y pedagógicas de la plataforma Moodle actual.</li>
    <li>Diseñar una arquitectura tecnológica moderna que permita la escalabilidad, seguridad e integración de herramientas educativas.</li>
    <li>Crear una interfaz intuitiva, accesible y responsive con múltiples dispositivos.</li>
    <li>Incorporar metodologías pedagógicas activas y personalizadas en el diseño de la plataforma.</li>
    <li>Probar y validar la nueva plataforma con usuarios reales mediante pruebas piloto.</li>
    <li>Establecer una estrategia de implementación, capacitación y soporte continuo.</li>
</ol>
<!-- Requisitos -->
<h2 id="requisitos">📋 Requisitos</h2>
<h3>Requerimientos funcionales:</h3>

| **Identificador** | **Nombre**                              | **Versión** | **Objetivos Asociados / Requisitos Asociados** | **Descripción / Precondición** | **Secuencia Normal / Postcondición / Excepciones** | **Importancia** |
|------------------|--------------------------------------|------------|-----------------------------------------------|--------------------------------|--------------------------------------------------|--------------|
| RF-01           | Registro de usuarios                | 1.0        | Acceso a la plataforma / Creación de cuentas | Los usuarios deben registrarse con correo institucional. | 1. Usuario ingresa datos.<br>2. Sistema valida.<br>3. Cuenta creada.<br>**Post:** Usuario registrado.<br>**Excepción:** Correo no válido. | Alta         |
| RF-02           | Creación de cursos                  | 1.0        | Gestión de contenidos / Inscripción de estudiantes | Los profesores pueden crear cursos con módulos. | 1. Profesor ingresa detalles.<br>2. Sistema almacena.<br>**Post:** Curso creado.<br>**Excepción:** Curso sin nombre. | Alta         |
| RF-03           | Inscripción de estudiantes          | 1.0        | Registro en cursos / Acceso a materiales | Los estudiantes pueden inscribirse en cursos activos. | 1. Usuario selecciona curso.<br>2. Se verifica disponibilidad.<br>**Post:** Inscripción exitosa.<br>**Excepción:** Curso lleno. | Media        |
| RF-04           | Subida y calificación de tareas     | 1.0        | Evaluación académica / Notificaciones | Los estudiantes pueden subir tareas y los profesores pueden calificarlas. | 1. Estudiante sube archivo.<br>2. Profesor revisa.<br>3. Se asigna nota.<br>**Post:** Tarea calificada.<br>**Excepción:** Archivo incorrecto. | Alta         |

<h3>Requerimientos NO funcionales:</h3>

| **Requerimiento No Funcional** | **Categoría**         | **Métrica** |
|------------------------------|----------------------|------------|
| RNF-01                      | Rendimiento          | Tiempo de respuesta menor a 1 segundo para consultas de datos. |
| RNF-02                      | Seguridad            | Los datos de usuarios deben estar encriptados con AES-256. |
| RNF-03                      | Accesibilidad        | Cumplimiento con WCAG 2.1 para accesibilidad web. |
| RNF-04                      | Disponibilidad       | Uptime del servidor del 99.9% anual. |
| RNF-05                      | Compatibilidad       | Soporte en navegadores modernos (Chrome, Firefox, Edge, Safari). |


<h2 id="metodologia">🔍 Metodología de desarrollo:</h2>

<p></p>

<h3>Cronograma:</h3>

<h2 id="arquitectura">🏗️ Arquitectura del Proyecto:</h2>

<p>La arquitectura del proyecto está orientada a garantizar escalabilidad, seguridad, modularidad y experiencia de usuario. Se propone una arquitectura en capas con tecnologías modernas y componentes integrables.</p>

<ol>
  <li><strong>Patrón de arquitectura:</strong> Se propone MVC (Model-View-Controller) para organizar el backend en Spring Boot y el frontend en React.</li>
  <li><strong>Tecnologías utilizadas:</strong></li>
    <ul>
      <li><strong>Backend:</strong> Java 21, Spring Boot, JWT.</li>
      <p align="center">
        <a href="https://skillicons.dev">
          <img src="https://skillicons.dev/icons?i=java,maven,spring,docker&theme=dark&perline=4" />
        </a>
      </p>
      <li><strong>Frontend:</strong> React, TypeScript/JavaScript.</li>
      <p align="center">
        <a href="https://skillicons.dev">
          <img src="https://skillicons.dev/icons?i=ts,css,react,nodejs&theme=dark&perline=4" />
        </a>
      </p>
    </ul>
  <li><strong>Diagramas UML:</strong> draw.io</li>

  <p align="center">
    <img src="./docs/diagrams/use-case-diagram" alt="Diagrama de Casos de Uso" width="40%">
    <img src="" alt="Diagrama de Clases" width="40%">
  </p>

  <p align="center">
    <img src="" alt="Diagrama de Paquetes" width="40%">
    <img src="" alt="Diagrama de Secuencia" width="40%">
  </p>

  <p align="center">
    <img src="" alt="Diagrama de Actividad" width="40%">
    <img src="" alt="Diagrama de Estado" width="40%">
  </p>

  <p align="center">
    <img src="" alt="Diagrama de Despliegue" width="40%">
    <img src="" alt="Diagrama de Implementación" width="40%">
  </p>

  <p align="center">
    <img src="" alt="Modelo de Datos (ER)" width="70%">
  </p>


  <li><strong>📁 Estructura General del Proyecto:</strong></li>

    app/
    ├── backend/
    │   ├── src/
    │   │   ├── main/
    │   │   │   ├── java/
    │   │   │   │   └── com/ibero/campus/
    │   │   │   │       ├── config/
    │   │   │   │       ├── controller/
    │   │   │   │       ├── model
    │   │   │   │       ├── repository/
    │   │   │   │       └── service/
    │   │   │   └── resources/
    │   │   │       ├── application.properties
    │   │   │       └── static/
    │   │   └── test/
    │   │       └── java/
    │   └── pom.xml    
    │
    ├── frontend/
    │   ├── package.json
    │   ├── public/
    │   ├── src/
    │   │   ├── assets/
    │   │   ├── components/
    │   │   ├── contexts/
    │   │   ├── hooks/
    │   │   ├── pages/
    │   │   ├── layouts/
    │   │   ├── services/
    │   │   ├── routes/
    │   │   ├── styles/
    │   │   ├── App.jsx   
    │   │   └── main.jsx
    │   ├── index.html
    │   ├── package.json
    │   ├── package-lock.json
    │   └── vite.config.js
    │
    ├── docs/
    │   ├── api/
    │   ├── architecture/
    │   ├── diagrams/
    │   ├── user-stories/
    │   ├── ux-ui/
    │   └── changelog.md  
    └── .gitignore
    └── README.md
  
  <li><strong>Maven:</strong> pom.xml</li>

  ```bash
  <project>
    <modelVersion>4.0.0</modelVersion>
    <groupId>com.ibero</groupId>
    <artifactId>backend</artifactId>
    <version>1.0.0</version>
    <properties>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        <maven.compiler.release>21</maven.compiler.release>
    </properties>
    <dependencies>

      <!-- Spring Web -->

      <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
      </dependency>

    <!-- Spring Security -->

    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-security</artifactId>
    </dependency>

    <!-- JPA + DB -->

    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>
    <dependency>
      <groupId>com.h2database</groupId>
      <artifactId>h2</artifactId>
      <scope>runtime</scope>
    </dependency>
    
    <!-- JWT -->

    <dependency>
      <groupId>io.jsonwebtoken</groupId>
      <artifactId>jjwt</artifactId>
      <version>0.9.1</version>
    </dependency>

    <!-- Validación -->

    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-validation</artifactId>
    </dependency>
  </dependencies>
  </project>
  ```
</ol>

  <li><strong>UX/UI:</strong> Figma</li>
  <p align="center">
        <a href="https://skillicons.dev">
          <img src="https://skillicons.dev/icons?i=figma&theme=dark&perline=4" />
        </a>
      </p>

---