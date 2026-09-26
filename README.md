<div align="center">

# Marco Salazar

**Backend Engineer · Python**

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

<table>
<tr>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="48" alt="Python"><br><sub>Python</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" width="48" alt="FastAPI"><br><sub>FastAPI</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlalchemy/sqlalchemy-original.svg" width="48" alt="SQLAlchemy"><br><sub>SQLAlchemy 2.0</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/swagger/swagger-original.svg" width="48" alt="OpenAPI"><br><sub>OpenAPI 3.1</sub></td>
</tr>
</table>

### Datos

<table>
<tr>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="48" alt="PostgreSQL"><br><sub>PostgreSQL 17</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original.svg" width="48" alt="Redis"><br><sub>Redis 8</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" width="48" alt="SQLite"><br><sub>SQLite</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" width="48" alt="pandas"><br><sub>pandas</sub></td>
</tr>
</table>

### Infraestructura

<table>
<tr>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="48" alt="Docker"><br><sub>Docker Compose</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="48" alt="Git"><br><sub>Git</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="48" alt="Linux"><br><sub>Linux</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" width="48" alt="Bash"><br><sub>Bash</sub></td>
</tr>
</table>

### Calidad y herramientas

<table>
<tr>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytest/pytest-original.svg" width="48" alt="pytest"><br><sub>pytest</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" width="48" alt="Visual Studio Code"><br><sub>VS Code</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pycharm/pycharm-original.svg" width="48" alt="PyCharm"><br><sub>PyCharm</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/qt/qt-original.svg" width="48" alt="Qt"><br><sub>PySide6</sub></td>
</tr>
</table>

### También manejo

<table>
<tr>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" width="42" alt="HTML5"><br><sub>HTML5</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" width="42" alt="CSS3"><br><sub>CSS3</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="42" alt="JavaScript"><br><sub>JavaScript</sub></td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" width="42" alt="Tailwind CSS"><br><sub>Tailwind CSS</sub></td>
</tr>
</table>

**Sin icono propio en devicon** — Pydantic · JWT · bcrypt · RBAC · Repository Pattern · Uvicorn · psycopg 3 · openpyxl · PyInstaller

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
