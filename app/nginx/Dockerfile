FROM nginx

# Remove the default configuration
RUN rm /etc/nginx/conf.d/default.conf

# Replace with the own nginx.conf
COPY nginx.conf /etc/nginx/conf.d/
