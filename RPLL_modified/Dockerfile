# Gunakan image PHP dengan Apache
FROM php:8.2-apache

# Salin semua isi folder proyek ke dalam container
COPY . /var/www/html/

# Aktifkan mod_rewrite jika kamu pakai .htaccess
RUN a2enmod rewrite

# Buka port 80 (port default Apache)
EXPOSE 80
