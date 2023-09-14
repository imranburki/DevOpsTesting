FROM node:alpine

WORKDIR /DevOpsTesting

COPY ./package.json /DevOpsTesting

RUN npm install

COPY . /DevOpsTesting

CMD ["npm","start"]