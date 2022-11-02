FROM node:latest
RUN mkdir -p /src/app
WORKDIR /src/app
RUN cd /src/app
COPY ./package.json ./
COPY . /src/app
EXPOSE 3003
CMD [ "npm", "start" ]