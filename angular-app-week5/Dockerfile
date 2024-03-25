# Use the official Nginx image as a base
FROM nginx:alpine

# Copy the built Angular app into the Nginx directory
COPY dist/angular-app-week5 /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Command to run Nginx
CMD ["nginx", "-g", "daemon off;"]