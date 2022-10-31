FROM node:latest
RUN mkdir -p /src/app
COPY package.json /src/app/package.json
WORKDIR /src/app
RUN npm install
COPY . /src/app
EXPOSE 3003
CMD [ "npm", "start" ]