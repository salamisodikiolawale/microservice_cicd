FROM node:latest
RUN mkdir -p /src/app
WORKDIR /src/app
COPY microservices/CrudMovieService .
RUN npm install
EXPOSE 3000
CMD [ "npm", "start" ]