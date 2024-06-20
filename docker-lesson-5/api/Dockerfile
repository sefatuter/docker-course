FROM node:17-alpine
# First layer is the parent layer
# get version 17. node and use the alpine distribution linux

WORKDIR /app
# doing installs in working directory

COPY . .
# copy all source code into the image ( COPY source dest , . -> current directory)

RUN npm install
# now we need to install dependencies to the image 

EXPOSE 4000
# which port

CMD ["node", "app.js"]
# run 