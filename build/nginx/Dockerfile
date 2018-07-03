FROM nginx:1.13.0

# move nginx config into correct location
COPY ./default.conf /etc/nginx/conf.d/default.conf

# Use the "exec" form of CMD so Nginx shuts down gracefully on SIGTERM (i.e. `docker stop`)
CMD [ "nginx", "-g", "daemon off;" ]
