# Use the official image as a parent image
# Description: Dockerfile for the client side of the MERN stack application

# Use the official image as a parent image
FROM node:18.9.1

WORKDIR /app

COPY package.json .

RUN npm install

EXPOSE 5173

COPY . .

# Run the specified command within the container
CMD ["npm", "run", "dev"]
