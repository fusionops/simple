FROM docker.io/httpd:2.4
COPY index.html /usr/local/apache2/htdocs/
COPY httpd.conf /usr/local/apache2/conf/
RUN chown www-data /usr/local/apache2 -R && ls -l /usr/local/apache2
USER www-data
EXPOSE 8080
