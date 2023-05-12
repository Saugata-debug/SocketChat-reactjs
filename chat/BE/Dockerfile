FROM node:18

# make app dir
WORKDIR /build

COPY . /build

RUN npm install

EXPOSE 9000

CMD npm run start