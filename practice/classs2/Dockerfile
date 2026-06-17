FROM almalinux:9  
RUN dnf install -y nginx
copy index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80
