FROM node:alpine

# Owner
MAINTAINER Sunny Aggarwal <sunny.aggarwal@erricsson.com>

WORKDIR '/app'

COPY package.json .
RUN npm install
COPY . .

CMD ["npm","start"]
