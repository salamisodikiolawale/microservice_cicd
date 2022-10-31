FROM node:latest
RUN mkdir -p /src/app
WORKDIR /src/app
# COPY package.json /src/app/package.json
COPY --link /foo /src/app
RUN npm install
# COPY . /src/app
COPY --link /foo /src/app
EXPOSE 3003
CMD [ "npm", "start" ]