# Use Node.js image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy the rest of the service code
COPY . .

# Expose the port the service runs on (e.g., 5001 for match-service)
EXPOSE 5001

# Start the service
CMD ["node", "server.js"]

