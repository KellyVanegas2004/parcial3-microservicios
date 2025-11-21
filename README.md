# Parcial 3 - Microservicios en Go con MongoDB y Docker

Este proyecto implementa un **CRUD distribuido en microservicios** usando **Golang**, **MongoDB**, **Docker Compose** y **GitHub Actions (CI/CD)**.

Cada operación del CRUD (Create, Read, Update, Delete) se maneja como un **servicio independiente**, comunicándose con una misma base de datos MongoDB.

---

##  Estructura del Proyecto

Parcial3-sistemasOperativos/
│
├── services/
│ ├── create/ # POST - Crear un phone
│ ├── read/ # GET - Leer todos los phones
│ ├── update/ # PUT - Actualizar un phone
│ └── delete/ # DELETE - Eliminar un phone
│
├── docker-compose.yml
├── .github/workflows/ci.yml # CI con GitHub Actions
└── README.md

yaml
Copiar código

---

---


---

## Autor

**Kelly Dahiana Vanegas Ochoa**  
Universidad EAM  
Parcial #3 — Sistemas Operativos  
Noviembre 2025
