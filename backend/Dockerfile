# Dockerfile
FROM node:14-alpine

# Set the working directory
WORKDIR /app

# Copy application files
COPY . /app

# Install dependencies
RUN npm install

# Set the command to start the app
CMD ["node", "index.js"]
