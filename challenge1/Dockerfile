# Use official image of NGINX
FROM nginx:alpine

# Copy static assets into the NGINX server
COPY ./public /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
