# PIAM: Plataforma Interactiva de Aprendizaje Matemático

> **PIAM** es una solución web moderna diseñada para transformar la enseñanza de las matemáticas, llevando el legado del *Álgebra de Baldor* a un entorno digital interactivo. Con un enfoque estrictamente **mobile-first**, la plataforma busca optimizar el aprendizaje para el 88.9% de los usuarios que utilizan smartphones como herramienta principal.

![Estado](https://img.shields.io/badge/Estado-Desarrollo-success?style=flat-square)
![Laravel](https://img.shields.io/badge/Laravel-11-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.3-777BB4?style=flat-square&logo=php&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8.1-646CFF?style=flat-square&logo=vite&logoColor=white)

---

## 🚀 Estado Actual del Proyecto

Hemos finalizado con éxito la **Fase de Configuración del Entorno de Desarrollo** (Mes 3, Semana 2). El sistema cuenta con una arquitectura robusta basada en el stack **Laravel (Backend)** y **React (Frontend)**.

### Logros Técnicos Alcanzados:
* **Base de Datos:** Configurada y migrada exitosamente bajo el nombre `piam_db` en MySQL.
* **Autenticación:** Implementada mediante Laravel Breeze para una gestión profesional de perfiles de usuario.
* **Interfaz:** Instalación de React con Inertia.js para garantizar una interactividad avanzada.
* **Solución de Errores:** Se corrigió manualmente el archivo `resources/js/bootstrap.js` para habilitar las peticiones de Axios y la retroalimentación automática.

---

## 🛠️ Stack Tecnológico

| Componente | Tecnología |
| :--- | :--- |
| **Backend** | PHP 8.3 + Laravel 11 |
| **Frontend** | React + Vite |
| **Base de Datos** | MySQL (`piam_db`) |
| **Estilos** | Tailwind CSS (Enfoque *Mobile-first*) |

---

## 📦 Instalación y Configuración Local

Sigue estos pasos para replicar el entorno de desarrollo actual:

### 1. Clonar el repositorio y configurar variables
```bash
git clone <URL_DEL_REPOSITO>
cd piam
cp .env.example .env

---

```
## Instalación de dependencias de Backend (PHP)
```bash
composer install
php artisan key:generate
php artisan migrate
---

```
## Instalación de dependencias de Frontend (React)
```bash
composer install
php artisan key:generate
php artisan migrate
---

```
## Terminal Backend
```bash
npm install --force
---

```
## Terminal Frontend(Compilador Vite)
```bash
npm run dev
---