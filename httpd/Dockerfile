FROM docker.io/httpd:2.4
COPY index.html /usr/local/apache2/htdocs/
COPY httpd.conf /usr/local/apache2/conf/
RUN ls -l /usr/local/apache2
USER www-data
EXPOSE 8080
