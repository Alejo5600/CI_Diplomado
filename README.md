# CI_Diplomado

## El archivo .htaccess
    RewriteEngine On
    RewriteCond %{REQUEST_FILENAME} !-d
    RewriteCond %{REQUEST_FILENAME} !-f
    RewriteRule ^ index.php [L]
Este archivo deberá situarse en la raiz del proyecto
