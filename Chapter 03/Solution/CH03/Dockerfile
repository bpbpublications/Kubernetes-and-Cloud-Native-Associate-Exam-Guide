# Pull a base image  
FROM node:18-alpine 

# Set a working directory 
WORKDIR /app 

# Copy the app code into the working directory 
COPY . . 

# Install dependencies 
RUN yarn install –production 

# Start app 
CMD ["node", "src/index.js"] 

# Define the port on which the app is listening 
EXPOSE 3000
