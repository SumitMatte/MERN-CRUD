# Use an official Node.js runtime as the base image
FROM node:latest

# Set the working directory inside the container
#WORKDIR /mnt

# Copy package.json and package-lock.json to the working directory
COPY /root/MERN-CRUD/server /mnt

# Install dependencies
RUN npm install

# Expose the port your app runs on
EXPOSE 8080

# Define the command to run your app (replace 'index.js' with the actual entry point of your application)
CMD ["node", "index.js"]

