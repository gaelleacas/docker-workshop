FROM node:10
WORKDIR /app
COPY package.json /app
RUN yarn --pure-lockfile
COPY . /app
EXPOSE 8080
CMD yarn start