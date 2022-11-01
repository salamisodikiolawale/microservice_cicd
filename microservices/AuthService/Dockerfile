FROM node:latest
RUN mkdir -p /src/app
WORKDIR /src/app
COPY pack* /src/app/package.json
RUN npm install
COPY . /src/app
EXPOSE 3003
CMD [ "npm", "start" ]