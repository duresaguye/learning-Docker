# parent or base image
FROM node:17-alpine

#working directory in the container 
WORKDIR /app 

#copying the package.json source codes file to the working directory
COPY . .
#installing the dependencies
RUN npm install
#exposing the port 4000
EXPOSE 4000

#running the app
CMD ["node", "app.js"]