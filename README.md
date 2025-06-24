## Requisitos

- PHP >= 8.2
- Composer
- MySQL
- Laravel (v12+)

## Clonar y ejecutar

> **Importante:** Clona el proyecto dentro de la carpeta donde tu entorno local espera los proyectos:
>
> - **Laragon:** `C:\laragon\www`
> - **XAMPP:** `C:\xampp\htdocs`

```bash
# 1. Clona el repositorio
git clone https://github.com/devsantiagobm/task-manager-laravel.git laravel-api-santiago-barrera

cd laravel-api-santiago-barrera

# 2. Instala dependencias
composer install

# 3. Genera la clave de la app
php artisan key:generate

# 4. Abre el archivo .env y asegúrate de configurar los datos de conexión según tu entorno local
# DB_HOST=127.0.0.1
# DB_PORT=3306
# DB_USERNAME=root
# DB_PASSWORD=

# 5. Ejecuta las migraciones
php artisan migrate

# 6. Levanta el servidor local
php artisan serve

```

Probar la API
Una vez el servidor esté corriendo, puedes probar los endpoints en:

`http://localhost:8000/api/tasks`
`GET|POST|PUT|DELETE`

Para clonar el proyecto frontend y conectarlo con esta API, visita:
https://github.com/devsantiagobm/task-manager-frontend`
