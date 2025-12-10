# IES_ROMERO_PHP

# 🚗 Práctica Postgres

## 📌 Descripción
Esta práctica tiene como objetivo:
- Instalar postgres
- Configurar Pgadmin
---

## ✅ Instalación y configuración

### 1. Crear servidor postgres

Clonar repositorio

```
git clone https://github.com/gadiro2005-sys/docker-postgres.git
cd docker-postgres
```

Arrancamos el contendor docker para la práctica:

```
docker compose -f docker-compose.yml -p docker up -d
```
o de otra forma:
```
docker-compose up -d
```
Configuramos el PgAdmin con la siguiente configuración:
```
user: admin
password: admin
servidor: 127.0.0.1
puerto: 5445
database: mydatabase
```

Ahora podremos dar de alta datos en la base de datos.
