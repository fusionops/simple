FROM docker.io/httpd:2.4
COPY index.html /usr/local/apache2/htdocs/
COPY httpd.conf /usr/local/apache2/conf/
RUN chown 33:33 /usr/local/apache2/* -R
RUN chmod +x /usr/local/apache2 -R
EXPOSE 8080
