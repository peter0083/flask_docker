# dockerfile for nginx container
FROM nginx

# remove the default nginx.conf
RUN rm /etc/nginx/conf.d/default.conf

# replace with our own nginx.conf file
COPY nginx.conf /etc/nginx/conf.d/