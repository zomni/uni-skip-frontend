# 🛍️ Uni-Skip – Frontend

Este repositorio corresponde al FRONTEND del proyecto Uni-Skip.
Está desarrollado con Angular y representa la interfaz principal del sistema, permitiendo a los usuarios iniciar sesión, registrarse, seleccionar tiendas, ver menús, gestionar carrito de compras y acceder a secciones de perfil/configuración.

Este frontend consume servicios expuestos por el backend del proyecto (API).

--------------------------------------------------

<details>
<summary><strong>🧠 ¿Qué es Uni-Skip – Frontend?</strong></summary>

Uni-Skip – Frontend es una aplicación web desarrollada con Angular que permite:

✔ Autenticación de usuarios (login, registro, recuperación de contraseña)
✔ Navegación por secciones tipo tienda/menú
✔ Selección de tienda y visualización de menú por tienda
✔ Gestión de carrito de compras
✔ Acceso a perfil y configuración
✔ Comunicación con el backend mediante API HTTP

La URL base del backend se encuentra configurada en el código como:
http://localhost:3000

</details>

--------------------------------------------------

<details>
<summary><strong>📌 Funcionalidades principales</strong></summary>

🔐 Autenticación
- Login de cliente
- Registro de usuario
- Recuperación de contraseña (forgot-password)

🏬 Tienda y selección
- Pantalla de selección de tienda (store-selection)
- Vista principal de tienda (store)

📋 Menú por tienda
- Navegación hacia menú usando parámetro de ruta (menu/:storeId)
- Preparado para mostrar catálogo/menú según tienda seleccionada

🛒 Carrito de compras
- Vista dedicada de shopping-cart
- Servicio de carrito para manejo de productos y estado

👤 Perfil y configuración
- Pantalla de perfil (profile)
- Ajustes del usuario (settings)

🎉 Página de bienvenida
- Vista welcome-page para flujo inicial del sistema

</details>

--------------------------------------------------

<details>
<summary><strong>🛠 Tecnologías utilizadas</strong></summary>

- Angular – Framework principal
- TypeScript – Lenguaje base
- HTML – Vistas
- CSS / SCSS – Estilos
- Node.js – Entorno de desarrollo
- npm – Gestión de dependencias

</details>

--------------------------------------------------

<details>
<summary><strong>📂 Estructura del proyecto</strong></summary>

uni-skip-frontend/
├── angular.json
├── package.json
├── tsconfig.json
├── src/
│   ├── app/
│   │   ├── pages/
│   │   │   ├── costumer-login/
│   │   │   ├── register/
│   │   │   ├── forgot-password/
│   │   │   ├── store/
│   │   │   ├── store-selection/
│   │   │   ├── menu/
│   │   │   ├── shopping-cart/
│   │   │   ├── profile/
│   │   │   ├── settings/
│   │   │   └── welcome-page/
│   │   ├── services/
│   │   │   ├── auth.service.ts
│   │   │   ├── backend.service.ts
│   │   │   └── cart.service.ts
│   │   ├── guards/
│   │   ├── app-routing.module.ts
│   │   └── app.module.ts
│   └── assets/
│       └── (logos e imágenes del proyecto)
└── README.md

</details>

--------------------------------------------------

<details>
<summary><strong>🔗 Relación con el backend</strong></summary>

Este frontend consume servicios del backend del proyecto Uni-Skip.

Flujo de comunicación:

Frontend (Angular)
   ↓
Backend API (uni-skip-backend)

Para ejecutar el sistema completo:
- El backend debe estar corriendo (por defecto en http://localhost:3000)
- El frontend se ejecuta en desarrollo con Angular CLI

</details>

--------------------------------------------------

<details>
<summary><strong>🚀 Cómo ejecutar el proyecto localmente</strong></summary>

1. Requisitos
- Node.js (versión LTS)
- npm
- Angular CLI

2. Clonar el repositorio

git clone https://github.com/tu-usuario/uni-skip-frontend.git

3. Instalar dependencias

npm install

4. Ejecutar en desarrollo

npm run start

o también:

ng serve

5. Abrir en el navegador

http://localhost:4200

Nota: Asegúrate de que el backend esté levantado en http://localhost:3000 para consumo real de datos.

</details>

--------------------------------------------------

<details>
<summary><strong>📄 Licencia</strong></summary>

Repositorio de uso académico y demostrativo.
Puede ser modificado libremente para fines educativos o de práctica profesional.

</details>

--------------------------------------------------

