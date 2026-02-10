# 🚀 API Testing Portfolio - Restful-Booker

Este repositorio contiene una colección de Postman diseñada para testear el flujo completo de una API de reservas hoteleras.

## 🛠️ Herramientas y Tecnologías
* **Postman v11**: Creación y organización de colecciones.
* **JavaScript (Scripts de Test)**: Automatización de validaciones de Status Codes.
* **Gestión de Entornos**: Uso de variables de entorno para IDs y Tokens de seguridad.

## 📋 Escenarios de Prueba (CRUD)
Se validaron los siguientes puntos críticos:
1. **Autenticación**: Generación exitosa de Token mediante método POST.
2. **Creación (POST)**: Registro de nueva reserva y captura de ID dinámico.
3. **Actualización (PUT)**: Modificación de datos existentes utilizando el Token en el Header (Cookie).
4. **Eliminación (DELETE)**: Borrado del recurso y verificación de limpieza de datos.

## 🕵️ Troubleshooting (Resolución de Problemas)
Durante el desarrollo, se identificaron y resolvieron bloqueos de seguridad **403 Forbidden**, ajustando la configuración de los Headers de autenticación y la vigencia de los tokens dinámicos.
