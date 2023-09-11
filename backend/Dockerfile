# Use an official Node.js image as a parent image
FROM node:14

# Set the working directory in the container
WORKDIR /app

# Copy your backend application files to the container
COPY . .

# Install application dependencies
RUN npm install

# Expose port used by your Node.js application
EXPOSE 3000

# Start your Node.js application using PM2
CMD ["npm", "start"]
