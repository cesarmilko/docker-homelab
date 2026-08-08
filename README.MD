# 🐳 Docker Compose Configurations

Repositorio centralizado para el respaldo, documentación y gestión de mis configuraciones de **Docker Compose** e infraestructura personal.

---

## 📂 Estructura del Repositorio

Cada servicio se encuentra aislado en su propia carpeta con su archivo `docker-compose.yml` y plantilla de variables de entorno `.env.example`.

```text
.
├── traefik/            # Reverse Proxy & SSL Automático
├── portainer/          # Panel de administración web de Docker
├── cloudflared/        # Tunel de cloudflare
└── ...                 # Otros servicios independientes