![image](https://github.com/grupo3rolling/Backend-BurgerScript/assets/148919690/bc68ef2b-2694-4700-8d85-e247bb63bda6)

# Backend del Proyecto eCommerce Burger Script

Este backend está desarrollado utilizando Visual Studio Code con las siguientes tecnologías:
- Backend: JavaScript con Node.js y Express.js para el servidor.
- Base de Datos: MongoDB para almacenar los datos del eCommerce.

## Descripción
El backend del proyecto Burger Script otorga las siguientes funcionalidades:
- Gestión de usuarios y productos: Permite a los administradores gestionar usuarios, productos.
- Autenticación: Permite a los usuarios registrarse, iniciar sesión y cerrar sesión en el sistema.
- Base de Datos: Utiliza MongoDB para almacenar y gestionar la información del eCommerce.

## Estructura general del sitio

## Comandos
Para utilizar este proyecto se debe:

### 1. Clonar el repositorio:
#### Clona este repositorio desde GitHub ejecutando el siguiente comando en tu terminal:
#### git clone [URL del repositorio]

### 2. Para instalar las dependencias
npm i

### 3. Variables de Entorno
#### Se debe crear un archivo ".env" y copiar la siguiente variable de entorno:
- PORT = 'El puerto donde se va a ejecutar el backend ejemplo: X000'
- DDBB = 'Direccion de la base de datos de Mongo Atlas ejemplo: mongodb+srv://usuario:'
- BCRPYPT_SALT = 'Saltos en la encriptacion con Bcrpyt ejemplo: X0'

### 4. Para ejecutar nuestra app de react
npm run dev

## Librerias utilizadas
- bcrypt: "^5.1.1",
- cors: "^2.8.5",
- dotenv: "^16.4.5",
- express: "^4.19.2",
- jsonwebtoken: "^9.0.2",
- mongoose: "^8.3.1",
- morgan: "^1.10.0",
- nodemon: "^3.1.0"

## Desarrolladores
- Leandro Bader
- Marvel Surriable
- Andrea Saraza
- Javier Aguilar
- Kelvin Pucho 
