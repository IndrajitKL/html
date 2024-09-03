# Use an official Nginx image based on Debian as a base
FROM nginx:latest

# Copy HTML files into the Nginx web directory
COPY src/ /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
