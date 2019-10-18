FROM node:carbon
MAINTAINER Vimalesan (vimalesan.ceg@gmail.com)
WORKDIR ./
COPY src ./src
COPY package.json .
RUN npm install
EXPOSE 3000
CMD [ "npm", "run", "start" ]