# Turn rewriting on
Options +FollowSymLinks
RewriteEngine On
# Redirect requests to index.php
RewriteCond %{REQUEST_URI} !=/index.php
RewriteRule .* /index.php 

#ii pentru a fi salvat in ftp