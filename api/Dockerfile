FROM node:14.18.0-alpine3.14

WORKDIR /home/node/app/api

EXPOSE 8080

# COPY THE PACKAGE.JSON
# COPY package.json /home/node/app/
COPY package.json ./

RUN npm install

# DEPLOYMENT COMMANDS
# COPY ./ ./
# CMD ["npm", "start"]

# LOCAL DEVELOPMENT BOND MIND
RUN npm i -g nodemon
# CMD ["nodemon", "index.js"]

# -v "$(pwd):/home/node/app"