# Anuario Digital de Hogwarts — Reto 03

**Equipo** · El Legado Escamado

**Integrantes** · Iván Alonso, Kenneth Álvarez y Henri Tejada

El proyecto plantea un anuario digital para consultar y gestionar fichas de personajes de Hogwarts. La solución prevista reúne una API común, una aplicación de escritorio, una aplicación móvil nativa y un escenario interactivo 3D.

## Tecnologías previstas

| Módulo | Tecnologías |
| --- | --- |
| Backend y datos | Python, FastAPI, PostgreSQL, BaseX y pytest |
| Escritorio e informes | JavaFX, Maven y JasperReports |
| Móvil | Android nativo y Gradle |
| Escenario 3D | Unity y C# |
| Integración continua | GitHub Actions |

## Estructura del repositorio

| Ruta | Finalidad |
| --- | --- |
| `api/` | Backend, persistencia y pruebas |
| `desktop-javafx/` | Aplicación de escritorio e informes |
| `android/` | Aplicación móvil nativa |
| `unity/` | Escenario interactivo 3D |
| `docs/` | Diagramas UML, decisiones técnicas, manuales y evidencias |
| `.github/workflows/` | Futura configuración de CI/CD |
| `README.md` | Presentación del proyecto |
| `.gitignore` | Exclusiones del control de versiones |
