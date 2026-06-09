FROM ubuntu:22.04
RUN apt update && apt install nginx -y
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
copy home.html /usr/share/nginx/html