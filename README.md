# LaravelProyectoFemasActulizacion-02
 SitioWeb

# 1. Crear proyecto Laravel 12
composer create-project laravel/laravel femas
cd femas

# 2. Instalar dependencias (Tailwind incluido)
npm install

# 3. Compilar assets
npm run dev

# 4. En otra terminal
php artisan serve

## controladores y modelos

# 1. Crear HomeController (para la página principal)
php artisan make:controller HomeController

# 2. Crear Modelo + Migración + Controlador CRUD (para proyectos)
php artisan make:model Project -mcr

# 3. Crear controlador de Auth (login admin)
php artisan make:controller AuthController

# 4. Crear Middleware (proteger admin)
php artisan make:middleware AdminMiddleware