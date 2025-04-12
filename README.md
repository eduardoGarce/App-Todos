# TodoApp

Esta es una aplicación web diseñada para la administracion de tareas basicas.
Registrate y comienza a registrar tus tareas, podrás añadir nuevas tareas o eliminarlas, también podrás marcar como realizadas todas aquellas tareas culminadas, haslo de una manera facil e intuitiva con TodoApp 

---

## **Tecnologías utilizadas**

- **Diseño y prototipado:** Figma
- **Frontend:** HTML, CSS, TailwindCSS, JavaScript
- **Backend:** Node.js, Express
- **Base de datos:** MongoDB
- **Autenticación:** JSON Web Token (JWT), bcrypt, Cookie-Parser
- **Correo electrónico:** Nodemailer

---

## **Instalación y ejecución**

### 1. Clonar el repositorio

```bash
git clone https://github.com/eduardoGarce/InvManage.git
cd InvManage
```

### 2. Instalar las dependencias

Ejecuta el siguiente comando para instalar las dependencias del proyecto:

```bash
npm install
```

### 3. Ejecutar el servidor en modo desarrollo

```bash
npm run dev
```

### 4. Ejecutar en producción

```bash
npm run start
```

## **Dependencias**

El proyecto utiliza los siguientes paquetes:

- bcrypt → Encriptación de contraseñas
- cookie-parser → Manejo de cookies
- cors → Habilitación de CORS
- cross-env → Gestión de entornos
- dotenv → Manejo de variables de entorno
- express → Framework backend
- jsonwebtoken → Autenticación mediante tokens JWT
- mongoose → Conexión y manipulación de MongoDB
- morgan → Logger para desarrollo
- nodemailer → Envío de correos electrónicos
- nodemon → Recarga automática del servidor en modo desarrollo

---

## **Autenticación**

El proyecto utiliza JWT y cookies para la autenticación:

- Los usuarios deben registrarse y verificar su correo mediante un enlace enviado por Nodemailer.
- El middleware comprueba si el usuario está logueado antes de permitir el acceso a rutas protegidas.
- Los tokens JWT se almacenan en cookies para validar la sesión del usuario.

---

## **Uso básico**

- /app → Registro, chequeo y eliminación de tareas.

---

## Autores

- Eduardo Garcés.
