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
git clone https://github.com/devsantiagobm/task-manager-laravel.git

cd repositorio

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
