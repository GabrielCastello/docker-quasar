FROM node:12-alpine
WORKDIR /usr/src/app
RUN yarn global add @quasar/cli
COPY ["package.json", "package-lock.json*", "yarn.lock", "./"]
COPY . .