FROM docker.io/httpd:2.4
COPY index.html /usr/local/apache2/htdocs/
COPY httpd.conf /usr/local/apache2/conf/
RUN chown daemon.daemon /usr/local/apache2 -R && ls -l /usr/local/apache2
USER daemon
EXPOSE 8080
