FROM nginx
COPY ./default.conf /etc/nginx/conf.d/default.conf
COPY ./ws.conf /etc/nginx/ws.conf
COPY ./cors.conf /etc/nginx/cors.conf

# COPY ./cors.conf /var/app/current/cors.conf
# COPY ./ws.conf /var/app/current/ws.conf
# COPY ./default.conf /var/app/current/default.conf

#CMD ["docker", "run", "-p", "3013:3013", "-p", "3014:3014", "-p", "3015:3015", "-v", "aeternity.yaml:/home/aeternity/.aeternity/aeternity/aeternity.yaml", "aeternity/aeternity:v3.0.1"]