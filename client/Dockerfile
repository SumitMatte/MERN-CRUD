# Use an official Node.js runtime as the base image
FROM node:latest

# Set the working directory inside the container
#WORKDIR /mnt

# Copy package.json and package-lock.json to the working directory
COPY /root/MERN-CRUD/client/ /mnt

# Install dependencies
RUN npm install

# Expose the port your app runs on
EXPOSE 3000

# Define the command to run your app (replace 'index.js' with the actual entry point of your application)
CMD ["npm", "start"]

