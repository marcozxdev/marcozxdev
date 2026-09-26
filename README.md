<div align="center">

# Marco Salazar

**Backend Engineer | Software Developer | AI · Python**

</div>

<div align="center">

[![Open to work](https://img.shields.io/badge/Open%20to%20work-Backend%20Python-3fb950?style=flat-square&labelColor=1a1a1a)](https://www.linkedin.com/in/marco-salazar-3a39733b4/)
[![Followers](https://img.shields.io/github/followers/marcozxdev?style=flat-square&labelColor=1a1a1a&logo=github&logoColor=white&label=Followers)](https://github.com/marcozxdev?tab=followers)
[![Repos](https://img.shields.io/github/repos/marcozxdev?style=flat-square&labelColor=1a1a1a&label=Repos&logo=github&logoColor=white)](https://github.com/marcozxdev?tab=repositories)

</div>

<div align="center">

[LinkedIn](https://www.linkedin.com/in/marco-salazar-3a39733b4/) ·
[marcozxdev@gmail.com](mailto:marcozxdev@gmail.com) ·
[Quindío, Colombia](https://www.google.com/maps/search/?api=1&query=Quindio+Colombia)

</div>

<br>

---

## Stack

### Backend

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square)  ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)  ![SQLAlchemy 2.0](https://img.shields.io/badge/SQLAlchemy%202.0-6BA81B?logo=sqlalchemy&logoColor=white&style=flat-square)  ![OpenAPI 3.1](https://img.shields.io/badge/OpenAPI%203.1-6BA539?logo=openapiinitiative&logoColor=white&style=flat-square)

### Datos

![PostgreSQL 17](https://img.shields.io/badge/PostgreSQL%2017-4169E1?logo=postgresql&logoColor=white&style=flat-square)  ![Redis 8](https://img.shields.io/badge/Redis%208-DC382D?logo=redis&logoColor=white&style=flat-square)  ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white&style=flat-square)  ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white&style=flat-square)

### Infraestructura

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square)  ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=flat-square)  ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=flat-square)  ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=white&style=flat-square)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white&style=flat-square)

### Calidad y herramientas

![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white&style=flat-square)  ![PyCharm](https://img.shields.io/badge/PyCharm-21D789?logo=pycharm&logoColor=white&style=flat-square)  ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white&style=flat-square)

### Desktop y web

![PySide6](https://img.shields.io/badge/PySide6-41CD52?logo=qt&logoColor=white&style=flat-square)  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square)  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square)  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=white&style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=white&style=flat-square)

**Tecnologías sin icono propio** — Pydantic · JWT · bcrypt · RBAC · Repository Pattern · Uvicorn · psycopg 3 · openpyxl · PyInstaller

---

## Proyectos

### ⭐ [Northwind Enterprise API](https://github.com/marcozxdev/Northwind-Enterprise-API)

`Python` `FastAPI` `PostgreSQL 17` `Redis 8` `Docker`

API REST empresarial sobre la base de datos Northwind. 8 entidades de negocio.

| | |
|---|---|
| Python | 8.386 líneas · 60 módulos |
| Tests | **100 automatizados en verde** contra PostgreSQL y Redis reales |
| Roles | 6, con distinción 401 / 403 |
| Capas | `core` → `models` → `repositories` → `routers` → `schemas` |
| Cache | Redis con TTL por tipo de entidad e invalidación por patrón en escrituras |
| Infra | Docker Compose: API + PostgreSQL + Redis + pgAdmin |
| Patrones | `BaseRepository[ModelType]` con `TypeVar` acotado, soft-delete, OpenAPI 3.1 |

<br>

### [CountBooks](https://github.com/marcozxdev/CountBooks)

`Python` `PySide6` `SQLite` `pandas` `Apache-2.0`

Inventario de libros para bibliotecas personales: préstamos, donaciones y pérdidas. **Cuatro autores** en el mismo repositorio.

- 2.776 líneas separadas en UI → Servicio → Repositorio → Base de datos
- SQL parametrizado al 100% e índices en título, autor, categoría e ISBN
- Importación y exportación a Excel con pandas + openpyxl
- Empaquetado con PyInstaller para Linux y Windows

<br>

### [Task Tracker API](https://github.com/marcozxdev/task-tracker-API)

`Python` `FastAPI` `SQLite` `JWT`

Mi proyecto más largo: 42 commits repartidos en 7,5 meses.

- Autenticación JWT con hashing de contraseñas
- Claves foráneas con `ON DELETE CASCADE` y `PRAGMA foreign_keys` activo
- Colección de Postman documentada

<br>

### [gesPagos CLI](https://github.com/marcozxdev/gesPagos_CLI)

`Python` `SQLite` `bcrypt`

Terminal para registrar deudas, pagos y saldos, con empaquetado como binario autónomo.

---

## Trayectoria

**Nov 2025** — Primeros endpoints FastAPI. Sin tests, sin anotaciones de tipo, `except:` vacíos.

**Abr 2026** — CountBooks: licencia open source y trabajo con otros tres autores.

**Ago 2026** — Northwind: repositorios genéricos, RBAC, caché Redis, Docker Compose.

**Sep 2026** — Northwind: 100 tests en verde y 475 docstrings estilo Google.

Diez meses entre el primer endpoint y una suite de integración.

---

## Contacto

[LinkedIn](https://www.linkedin.com/in/marco-salazar-3a39733b4/) ·
[marcozxdev@gmail.com](mailto:marcozxdev@gmail.com)

Quindío, Colombia · Español nativo · Inglés técnico en progreso

---

<details>
<summary><b>English</b></summary>

<br>

# Marco Salazar

**Backend Engineer · Python**

[LinkedIn](https://www.linkedin.com/in/marco-salazar-3a39733b4/) ·
[marcozxdev@gmail.com](mailto:marcozxdev@gmail.com) ·
Quindío, Colombia

### Stack

**Backend** Python · FastAPI · SQLAlchemy 2.0 · OpenAPI 3.1
**Data** PostgreSQL 17 · Redis 8 · SQLite · pandas
**Infrastructure** Docker Compose · Git · Linux · Bash
**Quality** pytest · VS Code · PyCharm · PySide6
**Also** HTML5 · CSS3 · JavaScript · Tailwind CSS · Pydantic · JWT · bcrypt

### Projects

**[Northwind Enterprise API](https://github.com/marcozxdev/Northwind-Enterprise-API)** · Python · FastAPI · PostgreSQL 17 · Redis 8 · Docker
Enterprise REST API over the Northwind database. 8 business entities, 8,386 lines of Python across 60 modules.
- **100 automated tests passing** against real PostgreSQL and Redis
- 6 roles with correct 401 / 403 separation
- Layered architecture: `core` → `models` → `repositories` → `routers` → `schemas`
- Redis caching with tiered TTLs and pattern invalidation on writes
- Docker Compose: API + PostgreSQL + Redis + pgAdmin
- Generic `BaseRepository[ModelType]` with bounded `TypeVar`

**[CountBooks](https://github.com/marcozxdev/CountBooks)** · Python · PySide6 · SQLite · pandas · Apache-2.0
Book inventory for personal libraries: loans, donations and losses. **Four authors** on one repository.
- 2,776 lines split across UI → Service → Repository → Database
- 100% parameterized SQL, indexed on title, author, category and ISBN
- Excel import/export via pandas + openpyxl, packaged with PyInstaller

**[Task Tracker API](https://github.com/marcozxdev/task-tracker-API)** · Python · FastAPI · SQLite · JWT
My longest project: 42 commits over 7.5 months.

**[gesPagos CLI](https://github.com/marcozxdev/gesPagos_CLI)** · Python · SQLite · bcrypt
Terminal app for tracking debts, payments and balances.

### Trajectory

- **Nov 2025** — First FastAPI endpoints. No tests, no type annotations, empty `except:`.
- **Apr 2026** — CountBooks: open-source license, work alongside three other authors.
- **Aug 2026** — Northwind: generic repositories, RBAC, Redis caching, Docker Compose.
- **Sep 2026** — Northwind: 100 tests passing, 475 Google-style docstrings.

Ten months from a first endpoint to an integration suite.

### Contact

[LinkedIn](https://www.linkedin.com/in/marco-salazar-3a39733b4/) · [marcozxdev@gmail.com](mailto:marcozxdev@gmail.com)

</details>
