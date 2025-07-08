# Olimpiadas 2025 Web de Paquetes Turísticos

Este es un proyecto web desarrollado para una **Olimpíada Escolar**. El objetivo principal es permitir a los usuarios ver, buscar y comprar paquetes turísticos de manera simple y rápida.
El proyecto fue realizado en equipo. Cada integrante del grupo cumplió un rol específico.
---
## 👤 Mi rol 

Yo, me encargué principalmente de la, **base de datos** y de **autenticación** del sitio. Algunas de las tareas que realicé:

- Creación y configuración de la base de datos.
- Conexión de la base de datos con el sitio web.
- Implementación del sistema de login y registro.
- Autenticación con JSON Web Token (JWT).
- Gestión de cookies para guardar sesión del cliente.
- Separación de roles entre usuario común y administrador.
- Integración del sistema de pagos con **Mercado Pago**.
- Modificaciones en las tablas y campos de la base de datos según lo requerido.

---

## 🖥️ ¿Cómo usar la web?

La página tiene dos tipos de usuarios: **cliente** y **administrador**.

### 👥 Clientes

1. **Registrarse** desde la sección “Crear cuenta”.
2. **Iniciar sesión** con tus datos.
3. Buscar paquetes turísticos usando el buscador de vuelos.
4. Agregar los que te interesen al **carrito**.
5. Finalizar la compra mediante **Mercado Pago**.
6. Desde tu panel, podés **ver tus pedidos** o **cancelar alguno** si está pendiente.

### ⚙️ Administradores

1. Iniciar sesión como admin (requiere token especial).
2. Acceder al **panel de administración**.
3. Crear nuevos paquetes turísticos.
4. Ver todos los pedidos realizados por los usuarios.

---

## 🛠️ Cómo correr el proyecto localmente

1. Clonar el repositorio: git clone https://github.com/JesusBaute/Olimpiadas_2025.git
2. Instalar las dependencias necesarias (según el stack que uses).
3. Configurar las variables de entorno, como claves API, tokens y credenciales de la base de datos.
4. El proyecto se puede clonar y probar localmente, pero no al 100% de su funcionalidad debido a que faltan claves API (como las de Mercado Pago) y otros datos sensibles que no se incluyen en el repositorio por motivos de seguridad. Para que todo funcione correctamente, deberás añadir tus propias claves y configuraciones.
