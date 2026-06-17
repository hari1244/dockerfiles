FROM  alpine
RUN apk add --no-cache nginx
COPY index.html /usr/share/nginx/
CMD ["nginx", "-g", "daemon off;"]