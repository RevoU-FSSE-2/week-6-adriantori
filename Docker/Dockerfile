# Select node version (LTS:18)
FROM node:lts-slim

# Create app directory
WORKDIR /app

# Bundle app source
COPY . .

# Building code for production
RUN npm install

# Expose port
EXPOSE 3001

# run node server
CMD [ "node", "app.js" ]