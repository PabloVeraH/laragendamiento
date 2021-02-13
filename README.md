# Laravel 6 Agendamiento

Es un MVP para generar agendamiento que puede servir para diferentes negocios

## Características

- Usa el tema de [CoreUI](https://coreui.io/demo/#main.html) (Bootstrap 4)
- Usa la libreria para el calendario: [FullCalendar](https://fullcalendar.io/) (version 3)


## Como se usa

- Clonar el repositorio (git clone)
- Copie el archivo __.env.example__ hacia __.env__ y edite las variables de conexión y otras variables globales
- Ejecute __composer install__
- Ejecute __php artisan key:generate__
- Ejecuten __php artisan migrate --seed__
- Se puede loguear a la aplicacion en la URL `/login` URL poner las credenciales __admin@admin.com__ - __password__
- Se puede usar el archivo docker-compose para lanzar la aplicacion en local ejecutando ```docker-compose up -d``` si lo tiene instalado. Si no simplemente ejecute ```php artisan serve```