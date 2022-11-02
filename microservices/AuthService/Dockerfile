FROM node:latest
RUN mkdir -p /src/app
WORKDIR /src/app
COPY package.json /src/app/package.json
COPY . /src/app
EXPOSE 3003
CMD [ "npm", "start" ]


# FROM node:latest
# RUN mkdir -p /src/app
# WORKDIR /src/app
# COPY microservices/AuthService .
# # COPY . /src/app
# EXPOSE 3003
# CMD [ "npm", "start" ]