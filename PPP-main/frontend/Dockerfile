# Use Node.js image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy the rest of the frontend code
COPY . .

# Expose the port for the development server
EXPOSE 3000

# Start the React development server
CMD ["npm", "run", "dev"]

