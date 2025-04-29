<!-- comando para prender el servidor  -->
PHP ARTISAN SERVE

<!-- Para acomodar y tabular   -->
SHIFT + ALT + F 

Migraciones para crear tablas y tambien desahcer
php artisan migrate para migrar
php artisan migrate:rollback --step 1


Para salvarnos de ataques csrf
@csrf 
<input type="hidden" name="_token" value="{{ csrf_token() }}">

Cookise samesite para que puedan ser utilizadas en un solo sitio