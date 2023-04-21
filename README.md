# Laravel 10-Lang-es
Aquí se encuentra los archivos de Lang en español para su implementación en laravel 10

1. En su directorio raíz cree la carpeta lang utilizando el siguiente codigo en la terminal:

       php artisan lang:publish

      esto creara una carpeta llamada lang en su directorio raíz, dentro encontrara otra carpeta llamada ‘en’.

2. Al lado de 'en' ud deberá crear una nueva carpeta llamada ‘es’ en la cual copiara y pegara los archivos aqui expuestos que corresponden 
a la respectiva traducción:

        auth.php

        pagination.php

        passwords.php

        validation.php

3. Después ingrese al archivo carpeta config/app.php y cambie la línea

       'locale' => 'en', 
 
      Por:  

       'locale' => 'es',

Y ya tendrá laravel 10 en español 

