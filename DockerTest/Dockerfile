FROM node:9-slim
WORKDIR /newApp
COPY package.json /newApp
RUN npm install
COPY . /newApp
CMD [ "npm","start" ]