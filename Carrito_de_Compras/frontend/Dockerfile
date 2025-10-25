FROM nginx:stable-alpine
WORKDIR /usr/share/nginx/html
# El contexto de build copiará todo el frontend (HTML/CSS/JS)
COPY . .
# nginx expondrá el puerto 80 en el contenedor
EXPOSE 80
