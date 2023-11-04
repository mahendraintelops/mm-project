FROM node:18.15-alpine

# Set working directory
WORKDIR /app

# Add package.json to WORKDIR and install dependencies
COPY package*.json ./
RUN npm install

# Add source code files to WORKDIR
COPY . .


# Application port (optional)
EXPOSE 8080


# Container start command (DO NOT CHANGE and see note below)
CMD ["npm", "start"]