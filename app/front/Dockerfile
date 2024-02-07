FROM nginx:latest

WORKDIR /usr/share/nginx/html

COPY . .

ENV WS_BACK_URL=http://backend-service:5000

EXPOSE 80

ENTRYPOINT ["nginx", "-g", "daemon off;"]
