FROM docker.io/centos/nginx-116-centos7

ENV os="centos" \
    osversion="7"

#COPY nginx.conf /etc/nginx/
#COPY index.html /data/www/index.html
#VOLUME [ "/data/www" ]
EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]
