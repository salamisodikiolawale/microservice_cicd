FROM node:latest
RUN mkdir -p /src/app
WORKDIR /src/app
COPY microservices/AuthService . 
# COPY . /src/app
EXPOSE 3003
CMD [ "npm", "start" ]