<div align="center">

<img src="https://github.com/marcozxdev.png" alt="Marco Salazar" width="110" style="border-radius:50%;border:3px solid #2b6cb0;">

# Marco Salazar

**Backend Python Engineer — FastAPI · PostgreSQL · Redis · Docker**

Construyo APIs de producción con Python. Este es mi stack real, no mi stack aspiracional.

<!-- Reemplaza estos placeholders con tus datos reales antes de publicar -->
<!-- Email:    tu-email@ejemplo.com -->
<!-- LinkedIn: https://www.linkedin.com/in/tu-usuario/ -->

[GitHub](https://github.com/marcozxdev) · [Northwind API](https://github.com/marcozxdev/Northwind-Enterprise-API) · [LinkedIn](#) · [Email](#)

</div>

---

## 📊 En números

<div align="center">

| | |
|:---:|:---|
| **8** | repositorios públicos |
| **~20.300** | líneas de código escritas |
| **100** | tests automatizados en verde |
| **109** | commits con Conventional Commits |
| **10** | meses de trayectoria documentada |

</div>

---

## 🛠️ Stack

### Backend
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="45" alt="Python">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" width="45" alt="FastAPI">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlalchemy/sqlalchemy-original.svg" width="45" alt="SQLAlchemy">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/swagger/swagger-original.svg" width="45" alt="OpenAPI">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" width="45" alt="NumPy">

### Datos
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="45" alt="PostgreSQL">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original.svg" width="45" alt="Redis">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" width="45" alt="SQLite">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" width="45" alt="pandas">

### Infraestructura
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="45" alt="Docker">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="45" alt="Linux">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="45" alt="Git">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" width="45" alt="GitHub">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" width="45" alt="Bash">

### Calidad y herramientas
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytest/pytest-original.svg" width="45" alt="pytest">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" width="45" alt="VS Code">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pycharm/pycharm-original.svg" width="45" alt="PyCharm">

### También manejo
<img height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/qt/qt-original.svg" alt="Qt / PySide6">
<img height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="HTML5">
<img height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="CSS3">
<img height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JavaScript">
<img height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS">

**Prácticas:** JWT + bcrypt · RBAC · Repository Pattern genérico · caché con invalidación · OpenAPI 3.1 · PyInstaller · typed settings con `pydantic-settings`

---

## 🚀 Proyectos

### ⭐ Northwind Enterprise API — *API REST empresarial*
**[`Northwind-Enterprise-API`](https://github.com/marcozxdev/Northwind-Enterprise-API)** · Python · FastAPI · PostgreSQL 17 · Redis 8 · Docker

API REST completa sobre la base de datos Northwind: 8 entidades de negocio, ~8.400 líneas.

- **Arquitectura por capas** — `core` → `models` → `repositories` → `routers` → `schemas`
- **100 tests automatizados** en verde, con aislamiento por rollback de transacción
- **RBAC con 6 roles** (`admin`, `manager`, `vendedor`, `viewer`, `auditor`, `inactive`) y distinción correcta entre 401 y 403
- **Caché en Redis** con TTL escalonado por tipo de entidad e invalidación automática por patrón en escrituras
- **Docker Compose** con 4 servicios: API, PostgreSQL 17, Redis y pgAdmin
- Repositorios genéricos `BaseRepository[ModelType]` con `TypeVar` acotado
- SQLAlchemy 2.0 moderno (`DeclarativeBase`, `Mapped[T]`, `mapped_column`) + psycopg 3

---

### 📚 CountBooks — *Gestor de biblioteca de escritorio*
**[`CountBooks`](https://github.com/marcozxdev/CountBooks)** · Python · PySide6 · SQLite · pandas · Apache-2.0

Aplicación de escritorio para inventario de libros con préstamos, donaciones e IEEE. **Proyecto open source con 4 autores** (el único donde colaboré en equipo).

- **~2.800 líneas** con separación UI → Servicio → Repositorio → Base de datos
- **SQL 100% parametrizado** e índices en título, autor, categoría e ISBN
- Modo WAL en SQLite y PRAGMAs afinados
- Import/export en Excel con pandas + openpyxl
- Empaquetado con PyInstaller para Linux y Windows

---

### ✅ Task Tracker API — *API de tareas con JWT*
**[`task-tracker-API`](https://github.com/marcozxdev/task-tracker-API)** · Python · FastAPI · SQLite · JWT

**Mi proyecto de mayor duración: 42 commits a lo largo de 7,5 meses.** Aquí aprendí FastAPI.

- Autenticación JWT + hashing de contraseñas y esquema de usuarios y tareas
- Claves foráneas con `ON DELETE CASCADE` y `PRAGMA foreign_keys` activo
- Colección de Postman documentada

---

### 💰 gesPagos CLI — *Control de deudas y pagos*
**[`gesPagos_CLI`](https://github.com/marcozxdev/gesPagos_CLI)** · Python · SQLite · bcrypt

Aplicación de terminal para registrar deudas, pagos y saldos. SQL parametrizado con parámetros nombrados y empaquetado como binario autónomo.

---

## 📈 Mi trayectoria

No empecé sabiendo. Estos son los commits, no las promesas:

| Periodo | Qué cambió |
|:---|:---|
| **Nov 2025** — `task-tracker-API` | Primeros endpoints FastAPI. Cero tests, cero anotaciones de tipo, `except:` vacíos, dependencias faltantes en `requirements.txt`. |
| **Abr 2026** — `CountBooks` | Primer proyecto con licencia open source y trabajo real en equipo (4 autores). SQL parametrizado y separación por capas. |
| **Ago 2026** — `Northwind` | Salto a arquitectura enterprise: repositorios genéricos, RBAC, caché Redis, Docker Compose. |
| **Sep 2026** — `Northwind` | **100 tests automatizados** en verde, `conftest.py` de 298 líneas con aislamiento por rollback, 475 docstrings estilo Google, pipeline de CI. |

**Diez meses, de cero tests a un pipeline de CI con cobertura de pruebas de integración.**

---

## 🧭 Hacia dónde voy

- **IA aplicada a backend** — RAG y agentes sobre Python, no solo consume modelos
- **Despliegue y observabilidad** — llevar Northwind de `docker compose up` a un entorno real con métricas
- **Ingeniería de datos** — deepen en PostgreSQL, índices y modelado a escala

---

## 📫 Contacto

Disponible para **oportunidades de backend Python (Junior–Mid)** y proyectos de freelance.

<!-- Descomenta y completa estos datos -->
<!-- **Email:**    tu-email@ejemplo.com -->
<!-- **LinkedIn:** https://www.linkedin.com/in/tu-usuario/ -->

📍 Quindío, Colombia · 🌎 Español nativo · 🇬🇧 Inglés técnico (A2 → B1 en curso)

---

<details>
<summary><b>🇬🇧 English version</b></summary>

## Marco Salazar

**Backend Python Engineer — FastAPI · PostgreSQL · Redis · Docker**

I build production APIs with Python. This is my real stack, not my aspirational stack.

### 📊 By the numbers

| | |
|:---:|:---|
| **8** | public repositories |
| **~20,300** | lines of code written |
| **100** | automated tests passing |
| **109** | commits following Conventional Commits |
| **10** | months of documented progress |

### 🚀 Projects

**⭐ Northwind Enterprise API** · Python · FastAPI · PostgreSQL 17 · Redis 8 · Docker
Full REST API over the Northwind sample database — 8 business entities, ~8,400 lines.
- Clean layered architecture: `core` → `models` → `repositories` → `routers` → `schemas`
- **100 passing automated tests** with per-test transaction rollback isolation
- **RBAC with 6 roles**, correct 401 vs 403 distinction
- **Redis caching** with tiered TTLs and automatic pattern invalidation on writes
- **Docker Compose** with 4 services: API, PostgreSQL 17, Redis, pgAdmin
- Generic `BaseRepository[ModelType]` with bounded `TypeVar`
- Modern SQLAlchemy 2.0 (`DeclarativeBase`, `Mapped[T]`, `mapped_column`) + psycopg 3

**📚 CountBooks** · Python · PySide6 · SQLite · pandas · Apache-2.0
Desktop library inventory app with loans and donations tracking. **Open source with 4 authors** — the one project I collaborated on as a team.
- ~2,800 lines, UI → Service → Repository → database separation
- 100% parameterized SQL with indexes on title, author, category and ISBN
- Excel import/export, packaged with PyInstaller

**✅ Task Tracker API** · Python · FastAPI · SQLite · JWT
**My longest-running project: 42 commits over 7.5 months.** This is where I learned FastAPI.

**💰 gesPagos CLI** · Python · SQLite · bcrypt
Terminal app for tracking debts, payments and balances.

### 📈 My trajectory

I didn't start out knowing this. These are the commits, not the promises:

- **Nov 2025** — First FastAPI endpoints. Zero tests, zero type annotations, empty `except:`, missing dependencies.
- **Apr 2026** — First open-source licensed project and real team collaboration (4 authors).
- **Aug 2026** — Jump to enterprise architecture: generic repositories, RBAC, Redis caching, Docker Compose.
- **Sep 2026** — **100 passing automated tests**, 298-line `conftest.py`, 475 Google-style docstrings, CI pipeline.

**Ten months, from zero tests to a CI pipeline with integration test coverage.**

### 🧭 Where I'm headed

- **Applied AI for backend** — RAG and agents in Python, not just consuming models
- **Deployment and observability** — taking Northwind from `docker compose up` to a real environment
- **Data engineering** — going deeper on PostgreSQL, indexing and modeling at scale

### 📫 Contact

Open to **Python backend opportunities (Junior–Mid)** and freelance work.

📍 Quindío, Colombia · 🌎 Native Spanish speaker · 🇬🇧 Technical English (A2 → B1, in progress)

</details>

---

<div align="center">

<sub>Hecho con código, no con promesas.</sub><br>
<sub>Built with code, not with promises.</sub>

</div>
