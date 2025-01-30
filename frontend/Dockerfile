FROM node:14-alpine

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory


# Install dependencies


# Copy the entire application to the working directory
COPY . .
RUN npm install

# Expose the port the app runs on
EXPOSE 3000

# Command to run the server
CMD ["npm", "run", "dev"]
