<div align="center">

# Juan Bastos

### Desarrollador de Software · Java & Spring Boot · JavaScript · Automatización con IA

Construyo servicios backend con Java y Spring Boot, interfaces web con JavaScript<br>
y flujos de automatización con inteligencia artificial que resuelven procesos reales.

<a href="https://github.com/bastos0511/portafolio"><img src="https://img.shields.io/badge/Portafolio-0d1117?style=for-the-badge&logo=github&logoColor=white" alt="Portafolio"></a>
<a href="https://www.linkedin.com/in/juan-bastos-1079911b9"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:juakikc@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

</div>

---

## Sobre mí

Soy desarrollador de software y me enfoco en construir aplicaciones que resuelvan problemas concretos, no ejercicios aislados.

La mayor parte de mi trabajo actual está en el **backend con Java y Spring Boot**: diseño de APIs REST, modelado de datos con JPA/Hibernate y PostgreSQL, y protección de endpoints con Spring Security y JWT. En el **frontend** trabajo con JavaScript, HTML y CSS para construir interfaces claras y fáciles de usar.

También exploro cómo la **inteligencia artificial y la automatización** pueden reducir el trabajo repetitivo: construyo flujos con n8n, integro APIs de IA y experimento con generación aumentada por recuperación (RAG).

Me importa cómo está estructurado el software, no solo que funcione. Por eso fortalezco en cada proyecto mi comprensión de arquitectura de software, código limpio y buenas prácticas de ingeniería.

---

## Stack tecnológico

| Área | Tecnologías |
| :--- | :--- |
| **Lenguajes** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![Hibernate](https://img.shields.io/badge/JPA_/_Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Bases de datos** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **IA y automatización** | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![APIs de IA](https://img.shields.io/badge/APIs_de_IA-412991?style=flat-square&logo=openai&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-1f2937?style=flat-square) |
| **Herramientas** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

---

## Proyectos destacados

### 🗂️ CampusDesk

Sistema de gestión de incidentes basado en una API REST para registrar, hacer seguimiento y resolver incidencias dentro de una institución.

**Problema** — Los reportes de incidentes gestionados por canales informales se pierden, no tienen un responsable claro y no dejan un historial trazable.

**Solución** — Una API backend centralizada donde los incidentes se crean, asignan y actualizan mediante endpoints protegidos, con cada cambio persistido en una base de datos relacional.

**Stack** — Java · Spring Boot · Spring Security · JWT · PostgreSQL · JPA/Hibernate · Swagger

**Funcionalidades principales**
- API REST para crear, consultar y actualizar incidentes
- Autenticación y autorización sin estado con Spring Security y JWT
- Persistencia relacional con PostgreSQL a través de JPA/Hibernate
- Documentación interactiva de la API con Swagger
- Manejo centralizado de excepciones con respuestas de error consistentes

**Lo que aprendí** — Arquitectura por capas (controlador → servicio → repositorio), separación de responsabilidades, seguridad de una API REST de extremo a extremo, modelado de entidades con JPA y diseño de un manejo de errores predecible.

---

### 🤖 TRAMIA / JARVIS

Asistente con inteligencia artificial diseñado para guiar a las personas en trámites administrativos y automatizar parte del proceso.

**Problema** — Los trámites administrativos suelen ser confusos: los requisitos están dispersos en distintos documentos y las personas pierden tiempo buscando información en lugar de completar el proceso.

**Solución** — Un asistente que recupera información relevante de una base de conocimiento y responde en contexto, combinado con flujos automatizados que resuelven los pasos repetitivos.

**Stack** — n8n · APIs de IA · RAG · APIs REST

**Funcionalidades principales**
- Respuestas contextualizadas mediante generación aumentada por recuperación (RAG)
- Flujos automatizados orquestados con n8n
- Integración de servicios externos a través de APIs
- Procesamiento y estructuración de información sobre trámites

**Lo que aprendí** — Diseño de pipelines de automatización, conexión de modelos de IA con fuentes de datos reales y los compromisos prácticos de construir sistemas basados en LLM que deben dar respuestas confiables.

---

### 💰 Expense Tracker

Aplicación web para registrar y organizar gastos personales.

**Problema** — Sin una forma sencilla de registrar los gastos, es difícil saber en qué se va realmente el dinero.

**Solución** — Una interfaz ligera en el navegador que hace rápido y claro el registro y la revisión de gastos.

**Stack** — JavaScript · HTML5 · CSS3

**Funcionalidades principales**
- Registro y gestión de gastos mediante una interfaz limpia
- Presentación organizada de la información de gastos
- Manejo de datos del lado del cliente con JavaScript nativo
- Enfoque en usabilidad y jerarquía visual clara

**Lo que aprendí** — Manipulación del DOM, manejo del estado de la aplicación sin frameworks y diseño de interfaces pensadas en cómo las personas leen la información.

---

### 🌐 Portafolio

Mi portafolio personal: el punto central para conocer mis proyectos, habilidades e información de contacto.

**Stack** — HTML5 · CSS3 · JavaScript

**Repositorio** — [github.com/bastos0511/portafolio](https://github.com/bastos0511/portafolio)

---

## Prácticas de ingeniería

Mis proyectos exploran las prácticas que hacen que el software sea mantenible en el tiempo:

- **Arquitectura por capas** — controladores, servicios y repositorios con responsabilidades claras
- **Diseño de APIs RESTful** — recursos, métodos HTTP y códigos de estado consistentes
- **DTOs y validación** — separación entre el contrato de la API y las entidades de persistencia
- **Inyección de dependencias** — componentes desacoplados mediante el contenedor IoC de Spring
- **Manejo global de excepciones** — respuestas de error predecibles y bien estructuradas
- **Seguridad** — autenticación y autorización con Spring Security y JWT
- **Documentación de APIs** — endpoints autodocumentados con Swagger / OpenAPI
- **Control de versiones** — commits con sentido y repositorios organizados con Git

Actualmente estoy fortaleciendo la aplicación de los **principios SOLID** y el código limpio, refactorizando trabajos anteriores a medida que mi comprensión crece.

---

## Aprendiendo actualmente

- **Arquitectura de software** — diseño de sistemas que escalen más allá de un solo servicio
- **Docker** — contenerización de aplicaciones Spring Boot y sus bases de datos
- **Testing** — pruebas unitarias y de integración con JUnit y Mockito
- **Ingeniería de IA** — pipelines RAG más robustos y automatización impulsada por IA

---

## Actividad en GitHub

Uso GitHub como registro de trabajo: cada repositorio refleja un problema que decidí resolver y las decisiones de ingeniería detrás de él. Te invito a explorar el código, abrir un issue o escribirme con tus comentarios.

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=bastos0511&show_icons=true&hide_border=true&theme=github_dark&hide_title=true&locale=es" alt="Estadísticas de GitHub">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bastos0511&layout=compact&hide_border=true&theme=github_dark&locale=es" alt="Lenguajes más usados">

</div>

---

## Objetivos profesionales

- Integrarme a un equipo de ingeniería donde pueda aportar a software en producción y aprender de desarrolladores con experiencia
- Profundizar mi experiencia en backend con Java y Spring Boot
- Escribir código más limpio, mejor probado y mejor estructurado en cada proyecto
- Construir soluciones prácticas que combinen el desarrollo de software tradicional con IA y automatización

---

## Contacto

- **Portafolio** — [github.com/bastos0511/portafolio](https://github.com/bastos0511/portafolio)
- **GitHub** — [github.com/bastos0511](https://github.com/bastos0511)
- **LinkedIn** — [linkedin.com/in/juan-bastos-1079911b9](https://www.linkedin.com/in/juan-bastos-1079911b9)
- **Email** — [juakikc@gmail.com](mailto:juakikc@gmail.com)

Abierto a oportunidades como desarrollador de software junior, colaboraciones y conversaciones técnicas.

---

<div align="center">
<sub>Juan Bastos · Construyendo software con Java, JavaScript e IA</sub>
</div>
