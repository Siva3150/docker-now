FROM almalinux:9 
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
RUN rm -rf /usr/share/nginx/html/index.html 
COPY index.html /usr/share/nginx/html/index.html 