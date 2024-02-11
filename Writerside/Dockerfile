# Use a Node.js base image
FROM node:latest

# Set the working directory in the container
WORKDIR /usr/src/app

# Install http-server globally
RUN npm install -g http-server

# Copy the local files to the container
COPY . .

# Expose the port the app runs on
EXPOSE 5001

# Command to run the HTTP server
CMD ["http-server", "-p 5001"]

