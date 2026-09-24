# 📌 cetpro-back-micro-yml

Repositorio de configuración centralizada para los microservicios del sistema **CETPRO**.  
Este proyecto utiliza **Spring Cloud Config Server** para gestionar de forma central los parámetros de configuración (perfiles, credenciales, conexiones, etc.) de cada servicio backend.

---

## 🚀 Tecnologías
- **Spring Boot**
- **Spring Cloud Config**
- **YAML (.yml)** para configuración
- **PostgreSQL** (ejemplo de conexión)

---

## 📂 Estructura del repositorio
Los archivos `.yml` corresponden a cada microservicio y sus distintos perfiles de entorno:

cetpro-back-micro-yml/

│

├── eureka-server.yml

├── catalog-service.yml

├── auth-service.yml

├── finance-service.yml

└── api-gateway.yml
