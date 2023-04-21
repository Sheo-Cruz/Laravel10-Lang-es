# Laravel 10-Lang-es
Aquí se encuentra los archivos de Lang en español para su implementación en laravel 10

En su directorio raíz cree la carpeta lang utilizando el siguiente codigo en la terminal:

php artisan lang:publish

esto creara una carpeta llamada lang en su directorio raíz, dentro encontrara otra carpeta llamada ‘en’ ,
al lado de esta ud deberá crear una nueva carpeta llamada ‘es’ en la cual copiara y pegara los cuales corresponden 
a la debida traducción:

  auth.php

  pagination.php

  passwords.php

  validation.php

Después ingrese al archivo carpeta config/app.php y cambie la línea

 'locale' => 'en', 
 
 Por:  

'locale' => 'es',

Y ya tendrá laravel 10 en español 

