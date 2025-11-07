# 💼 UdeAJobs Platform

_Freelancers Platform_ es un sistema con una **arquitectura basada en células**, diseñado para construir una plataforma moderna que conecta candidatos y empleadores.  

Cada **célula** agrupa los servicios necesarios para operar de manera autónoma (autenticación, perfiles, proyectos, comunicación, etc.), lo que garantiza **resiliencia**, **independencia tecnológica** y **escalabilidad selectiva** por dominio.

---

## 🧩 Projects

### 🌐 General
| Proyecto | Descripción |
|-----------|-------------|
| [Frontend](https://github.com/Team-DAS/Frontend) | Aplicación web principal para candidatos y empleadores. |

---

### 🧭 Cell Router
| Proyecto | Descripción |
|-----------|-------------|
| [Cell Router](https://github.com/Team-DAS/cell-router) | Enrutamiento del tráfico externo hacia las diferentes células. |

---

### 👤 Profile Management Cell
| Proyecto | Descripción |
|-----------|-------------|
| [Profile Cell (Monorepo)](https://github.com/Team-DAS/profile-cell) | Célula responsable de la gestión de perfiles y recursos personales. Incluye:<br> • 🗂️ **File Service** – Manejo de archivos y documentos.<br> • 👤 **Profile Service** – Administración de datos de usuario y CV.<br> • 📊 **Dashboard Service** – Visualización de información y estadísticas.<br> • 🌐 **Profile Gateway** – Punto de entrada y enrutamiento interno. |

---

### 💼 Projects Market Cell
| Proyecto | Descripción |
|-----------|-------------|
| [Projects Cell (Monorepo)](https://github.com/Team-DAS/projects-cell) | Célula encargada del manejo del mercado de proyectos. Incluye:<br> • 🧩 **Categorization Service** – Gestión de categorías.<br> • 💼 **Projects Service** – Administración de proyectos publicados.<br> • 🔍 **Searching Service** – Motor de búsqueda y filtrado.<br> • 🌐 **Projects Gateway** – Enrutamiento y orquestación interna. |

---

### 🔐 Access and Identity Cell
| Proyecto | Descripción |
|-----------|-------------|
| [Identity Cell (Monorepo)](https://github.com/Team-DAS/identity-cell) | Célula encargada de la identidad digital y la gestión de accesos. Incluye:<br> • 🧍 **Account Service** – Manejo de cuentas y usuarios.<br> • 🔐 **Auth Service** – Autenticación y emisión de tokens.<br> • 🛡️ **AuthZ Service** – Autorización, roles y permisos.<br> • 🌐 **Identity Gateway** – Punto de entrada y balance interno. |

---

### 🔄 Life Cycle Cell
| Proyecto | Descripción |
|-----------|-------------|
| [Life Cycle Cell (Monorepo)](https://github.com/Team-DAS/lifecycle-cell) | Célula responsable del ciclo de vida de las interacciones. Incluye:<br> • 📨 **Application Service** – Gestión de postulaciones.<br> • 🔔 **Notification Service** – Manejo de notificaciones internas y externas.<br> • 💬 **Communication Service** – Mensajería entre candidatos y empleadores.<br> • 🌐 **LifeCycle Gateway** – Punto de entrada de la célula. |

---

### ⚙️ Infrastructure Cell
| Proyecto | Descripción |
|-----------|-------------|
| [Infrastructure Cell (Monorepo)](https://github.com/Team-DAS/infrastructure-cell) | Célula encargada de la observabilidad, mensajería y monitoreo del ecosistema. Incluye:<br> • 📈 **Prometheus** – Recolección de métricas y monitoreo de servicios.<br> • 📊 **Grafana** – Visualización y paneles de control.<br> • 📜 **Loki** – Centralización y consulta de logs.<br> • 🐇 **RabbitMQ** – Sistema de mensajería para eventos entre células. |

---

## 📚 Other

| Proyecto | Descripción |
|-----------|-------------|
| [Docs](https://github.com/Team-DAS/C4-Architecture) | Documentación técnica del sistema y la arquitectura de células. |
| [UI](https://www.figma.com/design/6m3CSKDoyHiY4cnmpgWg0m/UdeAJobs?node-id=4102-115205&t=GRYSz1yYmvUbi31t-1) | Diseños del Frontend y flujos de interacción. |

---

> _“Cada célula es independiente, pero todas juntas conforman un ecosistema coherente: UdeA Jobs.”_






