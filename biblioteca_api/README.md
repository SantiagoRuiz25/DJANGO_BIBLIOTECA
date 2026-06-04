# Sistema de Gestión de Biblioteca API 📚

Este proyecto consiste en una **API REST** completa y robusta diseñada para administrar el flujo operativo de una biblioteca, incluyendo el control de inventario de libros, gestión de autores, editoriales, usuarios, préstamos, devoluciones y multas.

---

## 📋 Información General

* **Nombre del Proyecto:** Sistema de Gestión de Biblioteca API
* **Autor:** [Anderson Kaleth Rodelo / Aprendiz]
* **Problema Desarrollado:** Automatización del control de préstamos de libros, cálculo de fechas de entrega y aplicación de restricciones operativas. La solución implementa **Soft Delete** (borrado lógico que mantiene visible la información del registro desactivado con `activo=False`), logs de auditoría en tiempo real y exportación de datos de todas las tablas directamente a documentos estructurados de Excel.

---

## 🛠️ Tecnologías Utilizadas

* **Python:** v3.13+ (Lenguaje de programación principal)
* **Django & Django REST Framework:** Framework web y toolkit para la construcción de la API REST versionada.
* **PostgreSQL:** Motor de base de datos relacional (configurado con esquemas personalizados).
* **Swagger (drf_yasg):** Documentación interactiva y automatizada de los endpoints para pruebas en tiempo real.

---