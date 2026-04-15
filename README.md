# 🔐 Laboratorio #2 - Implementación de Login en Laravel
**Alumno: Joseph Córdoba | Cédula: 8-1025-2381 | Grupo: 1GS131 | Profesora: Ingeniera Irina Fong**

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## 📌 Descripción
Este laboratorio tiene como objetivo implementar un sistema de autenticación (login) utilizando el framework Laravel, aplicando la arquitectura Modelo-Vista-Controlador (MVC).  

Se documenta el proceso completo desde la configuración del entorno hasta la ejecución final del sistema.

---

## 🎯 Objetivos

- Comprender la importancia de la documentación en proyectos de software.
- Aplicar la arquitectura MVC en Laravel.
- Implementar un sistema de autenticación (login).
- Identificar problemas y soluciones durante el desarrollo.

---

## 🧩 Arquitectura MVC en Laravel

- **Modelos (Models):** Representan la estructura de la base de datos.
- **Vistas (Views):** Interfaz de usuario (Blade).
- **Controladores (Controllers):** Manejan la lógica del sistema.
- **Rutas (Routes):** Definen las URLs del sistema.

---

## ⚙️ Requisitos Previos

- PHP 8.0 o superior  
- Composer  
- Laravel  
- XAMPP / WampServer / Laragon  
- Apache o Nginx  
- MySQL o MariaDB  
- Visual Studio Code  
- Node.js y npm (si aplica)  
- Sistema Operativo (Windows/Linux)

---

## 🚀 Instalación
**Es importante tener el Composer instalado antes de instalar el Laravel.**

Si no tienes el Composer instalado, puedes instalarlo aquí: [Descarga Composer aquí](https://getcomposer.org/download/)

**1. Crear archivo**
```bash
composer create-project laravel/laravel (Nombre de tu archivo)
```
**2. Configurar entorno (.env)**
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laboratoriolaravel1
DB_USERNAME=root
DB_PASSWORD=
```
**3. Crear base de datos**
1. Entrar a phpMyAdmin
2. Crear la base de datos a utilizar
3. Ejecutar migraciones
```bash
php artisan migrate
```
## 🔐 Instalación de Laravel Breeze
```bash
composer require laravel/breeze --dev
php artisan breeze:install
npm install
npm run dev
php artisan migrate
```
## 👾 Base de datos
Laravel utiliza migraciones para crear tablas automáticamente.

Tablas generadas:

- users
- migrations
- sessions

## 🗣️ Ejecución
```bash
composer run dev
```

## 🖼️ Pruebas del sistema
<p align="center">
  <img src="imagenes/Captura de pantalla 2026-04-14 205523.png" width="500">
</p>
<p align="center">
  <img src="imagenes/Captura de pantalla 2026-04-14 210437.png" width="500">
</p>

## 🚩🚩 Dificultades y Soluciones
**❌ El error principal que tuve fue no tener instalado el NPM.**

**✅ Solución: Instalar Node.js**

**❌ No tener el php.zip activado**

**✅ Solución: Corregir en el .txt para proceder con la instalación**

## 📚 Referencias
- https://laravel.com/docs/12.x 
-  https://laravel.com/docs/12.x/installation

## 🦶 Footer
**Este laboratorio ha sido desarrollado por el estudiante de la Universidad Tecnológica de Panamá:**

- Nombre: Joseph Córdoba
- Correo: josephcordoba2318@gmail.com
- Correo: joseph.cordoba@utp.ac.pa
- Curso: Desarrollo de Software VII
- Instructor del Laboratorio: Irina Fong.

## 📅 Fecha
14 de Abril del 2026
