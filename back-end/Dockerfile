FROM node

WORKDIR /usr/src/

COPY . /usr/src/

EXPOSE 4000

RUN npm i

RUN npm run build

CMD ["npm", "start"]