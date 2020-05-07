# Specify a base image
FROM node:alpine

# Set work directory
WORKDIR /home/app

# Copy package.json into container
COPY ./package.json ./

# Install dependencies
RUN npm install

# Copy project into container
COPY ./ ./

# Default command
CMD ["npm", "start"]