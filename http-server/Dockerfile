FROM httpd:2.4

# Copie des fichiers front buildés (Vue.js)
COPY dist/ /usr/local/apache2/htdocs/

COPY my-httpd.conf /usr/local/apache2/conf/httpd.conf
